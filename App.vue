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


import TraumaScreen from './Screens/Trauma/Trauma'
import TraumaDefinisi from './Screens/Trauma/TraumaDefinisi'
import TraumaEtiologi from './Screens/Trauma/TraumaEtiologi'
import TraumaKlasifikasi from './Screens/Trauma/TraumaKlasifikasi'
import TraumaTanda from './Screens/Trauma/TraumaTanda'
import TraumaPathways from './Screens/Trauma/TraumaPathways'
import TraumaDiagnostik from './Screens/Trauma/TraumaDiagnostik'
import TraumaPengobatan from './Screens/Trauma/TraumaPengobatan'
import TraumaDiagnosa from './Screens/Trauma/TraumaDiagnosa'
import TraumaDaftar from './Screens/Trauma/TraumaDaftar'

const StackNavigator = createStackNavigator(
  {
    Main: MainScreen,
    About: AboutScreen,
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
    
    Trauma: TraumaScreen,
    TraumaDefinisi : TraumaDefinisi,
    TraumaEtiologi : TraumaEtiologi,
    TraumaKlasifikasi : TraumaKlasifikasi,
    TraumaTanda : TraumaTanda,
    TraumaPathways : TraumaPathways,
    TraumaDiagnostik : TraumaDiagnostik,
    TraumaPengobatan : TraumaPengobatan,
    TraumaDiagnostik : TraumaDiagnostik,
    TraumaDiagnosa : TraumaDiagnosa,
    TraumaDaftar : TraumaDaftar,
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