<template>
  <app-navigator></app-navigator>
</template>

<script>
import {
  createAppContainer,
  createStackNavigator,
} from "vue-native-router";

import MainScreen from './Main'
import AnotherScreen from './Another'
import GlaukomaScreen from './Screens/Glaukoma/Glaukoma'
import TraumaScreen from './Screens/Trauma/Trauma'
import ButaWarnaScreen from './Screens/ButaWarna/ButaWarna'
import KonjungtivitisScreen from './Screens/Konjungtivitis/Konjungtivitis'
import KatarakScreen from './Screens/Katarak/Katarak'

const StackNavigator = createStackNavigator(
  {
    Main: MainScreen,
    Another: AnotherScreen,
    Glaukoma: GlaukomaScreen,
    Trauma: TraumaScreen,
    ButaWarna: ButaWarnaScreen,
    Konjungtivitis: KonjungtivitisScreen,
    Katarak: KatarakScreen,
  },
  {
    initialRouteName: 'Main',
  }
);

const AppNavigator = createAppContainer(StackNavigator);

export default {
  components: { AppNavigator },
}
</script>