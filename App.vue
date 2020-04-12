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


import ButaWarnaScreen from './Screens/ButaWarna/ButaWarna'
import ButaWarnaDefinisi from './Screens/ButaWarna/ButaWarnaDefinisi'
import ButaWarnaEtiologi from './Screens/ButaWarna/ButaWarnaEtiologi'
import ButaWarnaKlasifikasi from './Screens/ButaWarna/ButaWarnaKlasifikasi'
import ButaWarnaManifestasi from './Screens/ButaWarna/ButaWarnaManifestasi'
import ButaWarnaPemeriksaan from './Screens/ButaWarna/ButaWarnaPemeriksaan'
import ButaWarnaPengobatan from './Screens/ButaWarna/ButaWarnaPengobatan'
import ButaWarnaDiagnosa from './Screens/ButaWarna/ButaWarnaDiagnosa'



import KonjungtivitisScreen from './Screens/Konjungtivitis/Konjungtivitis'
import KonjungtivitisDefinisi from './Screens/Konjungtivitis/KonjungtivitisDefinisi'
import KonjungtivitisEtiologi from './Screens/Konjungtivitis/KonjungtivitisEtiologi'
import KonjungtivitisKlasifikasi from './Screens/Konjungtivitis/KonjungtivitisKlasifikasi'
import KonjungtivitisTanda from './Screens/Konjungtivitis/KonjungtivitisTanda'
import KonjungtivitisPemeriksaan from './Screens/Konjungtivitis/KonjungtivitisPemeriksaan'
import KonjungtivitisPengobatan from './Screens/Konjungtivitis/KonjungtivitisPengobatan'
import KonjungtivitisDiagnosa from './Screens/Konjungtivitis/KonjungtivitisDiagnosa'
import KonjungtivitisDaftar from './Screens/Konjungtivitis/KonjungtivitisDaftar'



import KatarakScreen from './Screens/Katarak/Katarak'
import KatarakDefinisi from './Screens/Katarak/KatarakDefinisi'
import KatarakEtiologi from './Screens/Katarak/KatarakEtiologi'
import KatarakGejala from './Screens/Katarak/KatarakGejala'
import KatarakStadium from './Screens/Katarak/KatarakStadium'
import KatarakPemeriksaan from './Screens/Katarak/KatarakPemeriksaan'
import KatarakPengobatan from './Screens/Katarak/KatarakPengobatan'
import KatarakPathways from './Screens/Katarak/KatarakPathways'
import KatarakDiagnosa from './Screens/Katarak/KatarakDiagnosa'
import KatarakDaftar from './Screens/Katarak/KatarakDaftar'

const StackNavigator = createStackNavigator(
  {
    Main: MainScreen,
    About: AboutScreen,

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
    TraumaPengobatan : TraumaPengobatan,
    TraumaDiagnostik : TraumaDiagnostik,
    TraumaDiagnosa : TraumaDiagnosa,
    TraumaDaftar : TraumaDaftar,

    
    ButaWarna: ButaWarnaScreen,
    ButaWarnaDefinisi : ButaWarnaDefinisi,
    ButaWarnaEtiologi : ButaWarnaEtiologi,
    ButaWarnaKlasifikasi : ButaWarnaKlasifikasi,
    ButaWarnaManifestasi : ButaWarnaManifestasi,
    ButaWarnaPemeriksaan : ButaWarnaPemeriksaan,
    ButaWarnaPengobatan : ButaWarnaPengobatan,
    ButaWarnaDiagnosa : ButaWarnaDiagnosa,

    Konjungtivitis: KonjungtivitisScreen,
    KonjungtivitisDefinisi :  KonjungtivitisDefinisi,
    KonjungtivitisEtiologi :  KonjungtivitisEtiologi,
    KonjungtivitisKlasifikasi :  KonjungtivitisKlasifikasi,
    KonjungtivitisTanda :  KonjungtivitisTanda,
    KonjungtivitisPemeriksaan :  KonjungtivitisPemeriksaan,
    KonjungtivitisPengobatan :  KonjungtivitisPengobatan,
    KonjungtivitisDiagnosa :  KonjungtivitisDiagnosa,
    KonjungtivitisDaftar :  KonjungtivitisDaftar,


    Katarak: KatarakScreen,
    KatarakDefinisi : KatarakDefinisi,
    KatarakEtiologi : KatarakEtiologi,
    KatarakGejala : KatarakGejala,
    KatarakStadium : KatarakStadium,
    KatarakPemeriksaan : KatarakPemeriksaan,
    KatarakPengobatan : KatarakPengobatan,
    KatarakPathways : KatarakPathways,
    KatarakDiagnosa : KatarakDiagnosa,
    KatarakDaftar : KatarakDaftar,
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