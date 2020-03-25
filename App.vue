<template>
  <app-navigator></app-navigator>
</template>

<script>
import {
  createAppContainer,
  createStackNavigator,
} from "vue-native-router";

import MainScreen from './Main'
import AboutScreen from './About'
import TraumaScreen from './Screens/Trauma/Trauma'
import ButaWarnaScreen from './Screens/ButaWarna/ButaWarna'
import KonjungtivitisScreen from './Screens/Konjungtivitis/Konjungtivitis'
import KatarakScreen from './Screens/Katarak/Katarak'


import GlaukomaScreen from './Screens/Glaukoma/Glaukoma'
import GlaukomaDeskripsi from './Screens/Glaukoma/GlaukomaDeskripsi'

const StackNavigator = createStackNavigator(
  {
    Main: MainScreen,
    About: AboutScreen,
    Glaukoma: GlaukomaScreen,
    Trauma: TraumaScreen,
    ButaWarna: ButaWarnaScreen,
    Konjungtivitis: KonjungtivitisScreen,
    Katarak: KatarakScreen,
    GlaukomaDeskripsi : GlaukomaDeskripsi,
  },
  {
    initialRouteName: 'Main',
  },
);

const AppNavigator = createAppContainer(StackNavigator);

export default {
  components: { AppNavigator },
}
</script>