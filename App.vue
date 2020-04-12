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
import GlaukomaDefinisi from './Screens/Glaukoma/GlaukomaDefinisi'
import GlaukomaKlasifikasi from './Screens/Glaukoma/GlaukomaKlasifikasi'
import GlaukomaEtiologi from './Screens/Glaukoma/GlaukomaEtiologi'
import GlaukomaPathways from './Screens/Glaukoma/GlaukomaPathways'
import GlaukomaManifestasi from './Screens/Glaukoma/GlaukomaManifestasi'
import GlaukomaDiagnostik from './Screens/Glaukoma/GlaukomaDiagnostik'
import GlaukomaDiagnosa from './Screens/Glaukoma/GlaukomaDiagnosa'
import GlaukomaPengobatan from './Screens/Glaukoma/GlaukomaPengobatan'
import GlaukomaSumber from './Screens/Glaukoma/GlaukomaSumber'

const StackNavigator = createStackNavigator(
  {
    Main: MainScreen,
    About: AboutScreen,
    Trauma: TraumaScreen,
    ButaWarna: ButaWarnaScreen,
    Konjungtivitis: KonjungtivitisScreen,
    Katarak: KatarakScreen,

    Glaukoma: GlaukomaScreen,
    GlaukomaDefinisi : GlaukomaDefinisi,
    GlaukomaKlasifikasi : GlaukomaKlasifikasi,
    GlaukomaEtiologi : GlaukomaEtiologi,
    GlaukomaPathways : GlaukomaPathways,
    GlaukomaManifestasi : GlaukomaManifestasi,
    GlaukomaDiagnostik : GlaukomaDiagnostik,
    GlaukomaDiagnosa : GlaukomaDiagnosa,
    GlaukomaPengobatan : GlaukomaPengobatan,
    GlaukomaSumber : GlaukomaSumber,
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