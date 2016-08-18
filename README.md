# OpenArabic Project (@ AvH Lehrstuhl für Digital Humanities, U Leipzig)

**Contents**:
- [General Description](#General-Description)
- [Prospects and Progress](#prospects-and-progress)
- [Text Description Tags](#text-description-tags)
- [Text currently included in the Coprus](#text-currently-included-in-the-coprus)

# General Description

The goal of the project is to build a machine-actionable corpus of premodern texts in Arabic to encourage computational analysis of Arabic literary tradition. Currently, most of the text are historical texts (chronicles, biographical collections, geographical treatises and gazetteers, thematic dictionaries); if you are interested in having other genres and forms, please, get in touch with us.

Most of the texts are coming from open online collections of premodern and modern Arabic texts, such as [http://shamela.ws/](http://shamela.ws/) and [http://shiaonlinelibrary.com/](http://shiaonlinelibrary.com/) (These texts have `Shamela+NUMBER` and `Shia+NUMBER`; some texts are coming from _al-Jāmiʿ al-kabīr_, which has been published on an external HDD and is not available online (`JK+NUMBER`). Initial metadata from these collections is preserved in the beginning of each file.

Currently uploaded have been automatically converted from their initial formats into `mARkdown` format—a flavor of `markdown` for tagging premodern Arabic text; they all require further editing, so that the structure of each text is tagged properly; the detailed description of `mARkdown` scheme and the tagging workflow can be found [http://maximromanov.github.io/mARkdown/](http://maximromanov.github.io/mARkdown/). When manual tagging is complete text will be converted into CTS-compliant XML format.

For the list of added books, see below (Mostly premodern chronicles, biographical collections, encyclopaedic dictionaries, gazetteers).

# Prospects and Progress

| *Texts* | *Status* |
|:--- | ------:|
| Total in the Collection | 10,393 |
| Unique texts | 7,781 |
| Added texts (listed below) | 597 |
| Orphans (no TXT) | 2 |

| *Texts* | *Status* |
|:--- | ------:|
| In Progress (`.inProgress`) | _pending_ |
| Completed (`.completed`) | _pending_ |
| Vetted (`.mARkdown`) | _pending_ |
| Converted to TEI XML  (`.xml`) | _pending_ |

# Text Description Tags

Tags follow the URI of a text in the following format `(TAGS: TAG,TAG,TAG)`. Combinations of tags specify the description of the text, for example, `BIO` refers to 'a biographical text', but `BIO,COL` refers more specifically to 'a biographical collection'. 

*****************************
* `BIB` : bibliographical
* `BIO` : biographical
* `CHR` : chronicle
* `COL` : collection, dictionary, anthology
* `GEN` : genealogical
* `GEO` : geographical
* `ONO` : onomastic
* `HAD` : hadith

*****************************
* `SHC` : a Šīʿī text

*****************************
* `DHB` : ‘al-Ḏahabī Corpus’—his sources _&_ his books 
* `ORPHAN` : _no text_, orphan

*****************************
**NB**: Title descriptions also have temporary tags (they start with `_`, an undescore), which are generated and updated automatically from the initial metadata. These tags are usefully suggestive, but not entirely reliable.

# Project/Folder structure

- everything is divided into centuries
- each century includes `data` folder
- `data` folder includes `author` folders
- `author` folders include `title` folders
- `title` folders include:
	- texts (often different versions)
	- `arc` folder, where zipped texts are preserved in their pre-formatted form
	- `PDF` folder, which include:
		- **urls.txt** with links to PDFs (for about 125 books), mostly on [archive.org](archive.org)), which can be downloaded with `wget -i urls.txt` (on 'command line' or 'Terminal')
			- on Mac/Linux all PDFs can be also downloaded with `make` command
			- `wget` must be installed on Windows (Macs usually have it)
		- to save space, PDFs are ignored in this GitHub repositories 
		- if you find new PDFs, add urls (one per line) into a new file **urls_additional.txt**. PDFs can be found via Google, most commonly on the following websites:
			- [http://waqfeya.com/](http://waqfeya.com/), with most links lead to [archive.org](archive.org)); other useful sites are:
			- [http://kt-b.com/](http://kt-b.com/) (books are often bulked into large collections, but the selection seems to be larger than on [http://waqfeya.com/](http://waqfeya.com/));
			- [http://bib-alex.com/](http://bib-alex.com/), which has scanned books from the Bibliotheca Alexandrina (unfortunately, most files are stored on file-sharing services and lots of links are already dead)
			- [http://wqf.me/](http://wqf.me/) for manuscripts (search is rather complicated though); most links lead to [archive.org](archive.org) as well.

<!-- AUTOGENERATED CONTENT -->

# Text currently included in the Coprus

## List of books by centuries (597 titles)

* **0100AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * _no texts at the moment_

* **0200AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `0110HasanBasri.FadailMakka `
    * `0195MuarrijSadusi.HadhfMinNasabQuraysh `
    * `0200AbuShis.Diwan `

* **0300AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `0204IbnKalbi.AnsabKhayl `
    * `0204IbnKalbi.JamharaAnsab `
    * `0204IbnKalbi.NasabMacad `
    * `0207Waqidi.FutuhSham `
    * `0207Waqidi.Maghazi `
    * `0207Waqidi.Ridda `
    * `0209MacmarIbnMuthanna.Khayl `
    * `0211AbuCatahiya.Diwan `
    * `0213IbnHisham.SiraNabawiyya `
    * `0213IbnHisham.Tijan `
    * `0222IbnBakkarDabi.AkhbarWafidat `
    * `0222IbnBakkarDabi.AkhbarWafidin `
    * `0228IbnHammadKhuzaci.Fitan `
    * `0230IbnSacd.TabaqatKubra `
    * `0231IbnSallamJumahi.TabaqatFuhulShucara `
    * `0233YahyaIbnMacin.MacrifaRijal `
    * `0233YahyaIbnMacin.MinKalamFiRijal `
    * `0233YahyaIbnMacin.TarikhIbnMacin `
    * `0234AbuHasanSacdi.TasmiyaManRuwiya `
    * `0236AbuCabdAllahZubayri.NasabQuraysh `
    * `0240KhalifaIbnKhayyat.Tabaqat `
    * `0240KhalifaIbnKhayyat.Tarikh `
    * `0241IbnHanbal.AsamiWaKuna `
    * `0241IbnHanbal.CilalWaMacrifa `
    * `0241IbnHanbal.FadailSahaba `
    * `0245MuhammadIbnHabib.MukhtalafQabail `
    * `0245MuhammadIbnHabib.MunammaqFiAkhbarQuraysh `
    * `0248AbuHatimSijistani.FuhulaShucara `
    * `0249Azraqi.AkhbarMakka `
    * `0255Jahiz.AmilWaMamul `
    * `0255Jahiz.BayanWaTabyin `
    * `0255Jahiz.Bighal `
    * `0255Jahiz.Bukhala `
    * `0255Jahiz.BursanWaCurjan `
    * `0255Jahiz.Cuthmaniya `
    * `0255Jahiz.Hayawan `
    * `0255Jahiz.MahasinWaAddad `
    * `0255Jahiz.MukhtarFiRaddCalaNasara `
    * `0255Jahiz.Rasail `
    * `0255Jahiz.TabsiraBiTijara `
    * `0255Jahiz.TajFiAkhlaq `
    * `0256Bukhari.Ducafa `
    * `0256Bukhari.DucafaSaghir `
    * `0256Bukhari.TarikhKabir `
    * `0256Bukhari.TarikhSaghir `
    * `0256ZubayrIbnBakkar.AkhbarMuwaffaqiyat `
    * `0256ZubayrIbnBakkar.JamharaNasabQuraysh `
    * `0256ZubayrIbnBakkar.Muntakhab `
    * `0257IbnCabdHakam.FutuhMisr `
    * `0259IbnYacqubJuzjani.AhwalRijal `
    * `0261AbuHasanCijli.MacrifaThiqat `
    * `0261Muslim.KunaWaAsma `
    * `0261Muslim.Munfaridat `
    * `0262AbuZaydNumayri.TarikhMadina `
    * `0264AbyZurca.Ducafa `
    * `0272Fakihi.AkhbarMakka `
    * `0276IbnQutaybaDinawari.AdabKatib `
    * `0276IbnQutaybaDinawari.Macarif `
    * `0277AbuHatimRazi.JarhWaTacdil `
    * `0277IbnSyfyanFasawi.MacrifaWaTarikh `
    * `0279Baladhuri.AnsabAshraf `
    * `0279Baladhuri.FutuhBuldan `
    * `0279IbnAbiKhaythama.TarikhKabir `
    * `0280IbnTayfur.Baghdad `
    * `0280IbnTayfur.BallaghatNisa `
    * `0281AbuZurcaDimashqi.Tarikh `
    * `0282AbuHanifaDinawari.AkhbarTiwal `
    * `0286Mubarrad.NasabCadnan `
    * `0287Dahhak.AhadWaMathani `
    * `0292Bahshal.TarikhWasit `
    * `0292Yacqubi.Buldan `
    * `0292Yacqubi.TarikhYacqubi `
    * `0296IbnMuctazz.Diwan `
    * `0296IbnMuctazz.TabaqatShucara `
    * `0296MuhammadIbnJarrah.ManIsmuhCamr `
    * `0300IbnKhurdadhbih.MasalikWaMamalik `
    * `0300MuallifMajhul.AkhbarDawlaCabbasiya `

* **0400AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `0301Bardiji.TabaqatAsma `
    * `0303Nasai.DucafaWaMatrukin `
    * `0303Nasai.FadailSahaba `
    * `0303Nasai.Tabaqat `
    * `0303Nasai.TasmiyaFuqaha `
    * `0303Nasai.TasmiyaManLamYarwi `
    * `0303Nasai.TasmiyaShuyukh `
    * `0306IbnHayyanDabbi.AkhbarQudat `
    * `0308IbnIbrahimJundi.FadailMadina `
    * `0308IbnIbrahimJundi.FadailMadina `
    * `0309IbnFadlan.Rihla `
    * `0310IbnAhmadDulabi.Dhariyya `
    * `0310IbnAhmadDulabi.KunaWaAsma `
    * `0310Tabari.JamicBayan `
    * `0310Tabari.MuntakhabMinDhayl `
    * `0310Tabari.Tarikh `
    * `0317AbuQasimBaghawi.MucjamSahaba `
    * `0317AbuQasimBaghawi.TarikhWafatShuyukh `
    * `0318AbuCurubaHarrani.MuntaqaMinTabaqat `
    * `0320CaribQurtubi.SilaTarikhTabari `
    * `0322AbuJacfarCuqayli.DucafaKabir `
    * `0322KatibBaghdadi.TarikhAimma `
    * `0330Sirafi.Rihla `
    * `0333AbuCarabTamimi.Mihan `
    * `0333AbuCarabTamimi.TabaqatCulama `
    * `0334IbnHaikHamdani.Iklil `
    * `0334IbnHaikHamdani.SifaJaziraCarab `
    * `0334IbnSacidQushayri.TarikhRaqqa `
    * `0337IbnIshaqZajjaji.Akhbar `
    * `0346Istakhri.MasalikWaMamalik `
    * `0346Mascudi.AkhbarZaman `
    * `0346Mascudi.MurujDhahab `
    * `0346Mascudi.TanbihWaIshraf `
    * `0347IbnYunusSadafi.Tarikh `
    * `0349IbnCumarMuqri.AkhbarNahwiyyin `
    * `0351IbnQanic.MucjamSahaba `
    * `0354IbnHibban.Majruhin `
    * `0354IbnHibban.MashahirCulamaAmsar `
    * `0354IbnHibban.Sira `
    * `0354IbnHibban.Thiqat `
    * `0355AbuFarajIsbahani.Aghani `
    * `0355AbuFarajIsbahani.Diyarat `
    * `0355MuhammadKindi.FadailMisr `
    * `0355MuhammadKindi.WulatMisr `
    * `0360Khawlani.TarikhDaraya `
    * `0360Tabarani.MucjamKabir `
    * `0365IbnCadiJurjani.AsamiManRawaCanhum `
    * `0365IbnCadiJurjani.KamilFiDucafa `
    * `0365IbnFaqihHamadhani.Buldan `
    * `0367IbnHawqal.SuraArd `
    * `0368AbuGhalibZurari.Risala `
    * `0368Sirafi.AkhbarNahwiyyin `
    * `0369AbuShaykhIsbahani.TabaqatMuhaddithin `
    * `0370IbnBishrAmidi.MutalifWaMukhtalif `
    * `0371AhmadJurjani.Mucjam `
    * `0374IbnHusaynAzdi.AsmaManYucrafBiKunya `
    * `0374IbnHusaynAzdi.Makhzun `
    * `0374IbnHusaynAzdi.ManWafaqaIsmuhuIsmAbihi `
    * `0379MuhammadRabci.TarikhMawlidCulama `
    * `0380Muhallabi.MasalikWaMamalik `
    * `0382IbnCabdAllahCaskari.AkhbarMusahhifin `
    * `0384IbnCimranMarzubani.MucjamShucara `
    * `0385Daruqutni.DhikrAsmaTabicin `
    * `0385Daruqutni.Ducafa `
    * `0385Daruqutni.MutalifWaMukhtalif `
    * `0385Daruqutni.SualatBarqani `
    * `0385Daruqutni.SualatNaysaburi `
    * `0385IbnNadim.Fihrist `
    * `0385IbnShahin.TarikhAsmaDucafa `
    * `0385IbnShahin.TarikhAsmaThiqat `
    * `0388Shabushti.Diyarat `
    * `0390Muqaddasi.AhsanTaqasim `
    * `0395IbnMandahMuhammad.Asami `
    * `0395IbnMandahMuhammad.FathBab `
    * `0395IbnMandahMuhammad.MacrifaSahaba `
    * `0398AbuNasrKalabadhi.HidayaWaIrshad `
    * `0400IbnTahirMaqdisi.BadWaTarikh `
    * `0400IshaqMunajjim.AkamMarjan `

* **0500AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `0402MuhammadSaydawi.MucjamShuyukh `
    * `0403IbnFaradi.TarikhCulamaAndalus `
    * `0405AbuFadlHarawi.MucjamFiMushtabah `
    * `0405HakimNaysaburi.TalkhisTarikhNaysabur `
    * `0405HakimNaysaburi.TasmiyaManAkhrajahum `
    * `0409CabdGhaniAzdi.KitabMutawarin `
    * `0412Sulami.TabaqatSufiya `
    * `0418WazirMaghribi.AdabKhawas `
    * `0418WazirMaghribi.Inas `
    * `0421IbnMuhammadMarzuqi.AzminaWaAmkina `
    * `0421Miskawayh.Tajarib `
    * `0427HamzaJurjani.TarikhJurjan `
    * `0428IbnManjuwayhIsbahani.RijalSahihMuslim `
    * `0429AbuMansurThacalibi.YatimaDahr `
    * `0429Thacalibi.ThimarQulub `
    * `0430AbuNucaymIsbahani.DhikrManIsmuhuShucba `
    * `0430AbuNucaymIsbahani.Ducafa `
    * `0430AbuNucaymIsbahani.HilyaAwliya `
    * `0430AbuNucaymIsbahani.MacrifaSahaba `
    * `0430AbuNucaymIsbahani.TarikhIsbahan `
    * `0430AbuNucaymIsbahani.TasmiyaMaIntahaIlayna `
    * `0436HusaynSaymari.AkhbarAbiHanifa `
    * `0440AbuRayhanBiruni.TahqiqMaLilHind `
    * `0442Tanukhi.TarikhCulamaNahwiyyin `
    * `0446AbuYaclaKhalili.IrshadFiMacrifaCulama `
    * `0448HilalSabi.TuhfaUmara `
    * `0449AbuCalaMacarri.Diwan `
    * `0450Najashi.Rijal `
    * `0456IbnHazm.AsmaKhulafa `
    * `0456IbnHazm.FadailAndalus `
    * `0456IbnHazm.JamharaAnsab `
    * `0456IbnHazm.NaqtCarus `
    * `0456IbnHazm.RisalaFiFutuhIslam `
    * `0456IbnHazm.RisalaFiMaratibCulum `
    * `0456IbnHazm.UmmahatKhulafa `
    * `0458Bayhaqi.DalailNubuwwa `
    * `0460ShaykhTusi.IkhtiyarMacrifaRijal `
    * `0460ShaykhTusi.Rijal `
    * `0463IbnCabdBarr.InbahCalaQabail `
    * `0463IbnCabdBarr.IsticabFiMacrifaAshab `
    * `0463KhatibBaghdadi.GhunyaMultamis `
    * `0463KhatibBaghdadi.MuttafiqWaMuftariq `
    * `0463KhatibBaghdadi.TalkhisMutashabih `
    * `0463KhatibBaghdadi.TarikhBaghdad `
    * `0466CabdAzizKattani.DhaylTarikhMawlidCulama `
    * `0469IbnHayyanQurtubi.Muqtabas `
    * `0474IbnKhalafBaji.TacdilWaTakhrij `
    * `0475IbnMakula.IkmalFiRafcIrtiyab `
    * `0475IbnMakula.TahdhibMustamirr `
    * `0476AbuIshaqShirazi.TabaqatFuqaha `
    * `0482AbuIshaqHabbal.WafayatMisriyyin `
    * `0487AbuCubaydBakri.MasalikWaMamalik `
    * `0487AbuCubaydBakri.MucjamMaIstacjama `
    * `0488IbnFutuhHumaydi.JadhwaMuqtabis `
    * `0498AbuCaliJayyani.AlqabSahaba `
    * `0498AbuCaliJayyani.TaqyidMuhmal `

* **0600AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `0507AbuBakrShashi.HilyaCulama `
    * `0507IbnQaysarani.AnsabMuttafiqa `
    * `0508FattalNaysaburi.RawdaWacizin `
    * `0511IbnMandahYahya.MacrifaAsamiArdaf `
    * `0511SalmaSahari.Ansab `
    * `0515IbnQattac.DurraKhatira `
    * `0521IbnAbiYacla.TabaqatHanabila `
    * `0521MuhammadHamadhani.TakmilaTarikhTabari `
    * `0524IbnAkfani.DhaylDhaylTarikhMawlidCulama `
    * `0528FathIbnKhaqan.QalaidCiqyan `
    * `0535QawwamSunna.DalailNubuwwa `
    * `0535QawwamSunna.SiyarSalaf `
    * `0538MahmudZamakhshari.JibalWaAmkina `
    * `0541IbnCatiyyaMuharibi.Fahrasa `
    * `0542IbnBassamShantarini.Dhakhira `
    * `0544CiyadIbnMusaYahsubi.Ghunya `
    * `0544CiyadIbnMusaYahsubi.TartibMadarik `
    * `0555IbnQalanisi.Tarikh `
    * `0560SharifIdrisi.NuzhaMushtaq `
    * `0561Samcani.Ansab `
    * `0561Samcani.Muntakhab `
    * `0561Samcani.Tahbir `
    * `0565IbnZaydBayhaqi.LubabAnsab `
    * `0565IbnZaydBayhaqi.TarikhBayhaq `
    * `0565IbnZaydBayhaqi.TatimmaSiwanHikma `
    * `0569CumaraHakami.NukatCasriyya `
    * `0571IbnCasakir.MucjamShuyukh `
    * `0571IbnCasakir.TarikhDimashq `
    * `0573NashwanHimyari.KhulasaSiyar `
    * `0575IbnBabawayh.Fihrist `
    * `0575IbnKhayrIshbili.Fahrasa `
    * `0576IbnMuhammadSilafi.Mashyakha `
    * `0576IbnMuhammadSilafi.MashyakhaBaghdadiyya `
    * `0576IbnMuhammadSilafi.MucjamSafar `
    * `0576IbnMuhammadSilafi.Wajiz `
    * `0577IbnAnbari.NuzhaAlibba `
    * `0578IbnBashkuwal.GhawamidAsma `
    * `0578IbnBashkuwal.Sila `
    * `0580IbnCimrani.InbaFiTarikhKhulafa `
    * `0584IbnMunqidhShayzari.Ictibar `
    * `0584IbnMusaHazimi.Amakin `
    * `0584IbnMusaHazimi.CujalaMubtadi `
    * `0597CimadDinKatib.BarqShami `
    * `0597CimadDinKatib.KharidaQasr `
    * `0597IbnJawzi.DucafaWaMatrukin `
    * `0597IbnJawzi.FadailQuds `
    * `0597IbnJawzi.Mashyakha `
    * `0597IbnJawzi.Muntazam `
    * `0597IbnJawzi.MuthirGharam `
    * `0597IbnJawzi.SifaSafwa `
    * `0597IbnJawzi.TalqihFuhum `
    * `0597IbnJawzi.TarikhBaytMuqaddas `
    * `0599IbnYahyaDabbi.BughyaMultamis `
    * `0600AbuBaqaHilli.ManaqibMazidiya `
    * `0600KatibMarrakushi.Istibsar `

* **0700AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `0606IbnMamati.LataifDhakhira `
    * `0611CaliHarawi.Isharat `
    * `0611SharafDinMuqaddasi.Arbacin `
    * `0614IbnJubayr.Rihla `
    * `0615MuwaffaqDinShafici.MurshidZuwwar `
    * `0617MansurIbnShahanshah.MidmarHaqaiq `
    * `0623Qazwini.Tadwin `
    * `0626YaqutHamawi.Khazal `
    * `0626YaqutHamawi.MucjamBuldan `
    * `0626YaqutHamawi.MucjamUdaba `
    * `0628IbnCaliSanhaji.AkhbarMuluk `
    * `0629IbnNuqta.IfadaWaIctibar `
    * `0629IbnNuqta.TakmilaIkmal `
    * `0629IbnNuqta.TaqyidLiMacrifa `
    * `0630IbnAthirCizzDin.Kamil `
    * `0630IbnAthirCizzDin.LubabFiTahdhibAnsab `
    * `0630IbnAthirCizzDin.UsdGhaba `
    * `0632AbyHafsSuhrawardi.Mashyakha `
    * `0632IsmacilMarwazi.FakhriFiAnsab `
    * `0637IbnMustafwi.TarikhIrbil `
    * `0639AbuBakrMalaqi.MatlacAnwar `
    * `0640AbuHafsDunaysiri.TarikhDunaysir `
    * `0641Sarifini.Muntakhab `
    * `0642IbnNajjar.DhaylTarikhBaghdad `
    * `0643DiyaDinMuqaddasi.FadailBaytMaqdis `
    * `0643DiyaDinMuqaddasi.JuzAwham `
    * `0643IbnSalahShahrazuri.TabaqatFuqaha `
    * `0645TilimsaniBurri.Jawhara `
    * `0646IbnQifti.IkhbarCulama `
    * `0646IbnQifti.InbahRuwat `
    * `0646IbnQifti.Muhammadun `
    * `0647CabdWahidMarrakushi.Mucjib `
    * `0650IbnNazifHamawi.TarikhMansuri `
    * `0657IbnIbrahimIrbili.MudhakaraFiAlqab `
    * `0658IbnAbbar.HullaSiyara `
    * `0658IbnAbbar.MucjamAshab `
    * `0658IbnAbbar.TakmilaLiSila `
    * `0658IbnAbbar.TuhfaQadim `
    * `0659SainDinNaccal.Mashyakha `
    * `0660IbnCadim.BughyatTalib `
    * `0660IbnCadim.ZubdaHalab `
    * `0665AbuShama.Rawdatayn `
    * `0668IbnAbiUsaybica.CuyunAnba `
    * `0673AbuMahasinYaghmuri.NurQabas `
    * `0676Nawawi.TahdhibAsma `
    * `0677SahibTaji.HalbaFiAsmaKhayl `
    * `0680IbnSabuni.TakmilaIkmalIkmal `
    * `0681IbnKhallikan.WafayatAcyan `
    * `0682ZakariyaQazwini.AtharBilad `
    * `0684IbnShaddad.AclaqKhatira `
    * `0685IbnCibri.TarikhMukhtasarDuwal `
    * `0685IbnSacidMaghribi.GhusunYanica `
    * `0685IbnSacidMaghribi.Jughrafiya `
    * `0685IbnSacidMaghribi.Mughrib `
    * `0690IbnMujawirDimashqi.TarikhMustabsir `
    * `0691IbnYusufLabli.Fihrist `
    * `0694MuhibbDinTabari.Dhakhair `
    * `0694MuhibbDinTabari.RiyadNadira `
    * `0695IbnCidhariMarrakushi.BayanMaghrib `
    * `0696Dabbagh.MacalimIman `
    * `0696IbnZahiri.Mashyakha `

* **0800AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `0701SharafDinYunini.Mashyakha `
    * `0703MuhammadMarrakushi.DhaylWaTakmila `
    * `0705SharafDinDimyatti.MucjamShuyukh `
    * `0709CaliCalawi.Majdi `
    * `0711IbnManzurIfriqi.MukhtasarTarikhDimashq `
    * `0714AhmadGhibrini.CunwanDiraya `
    * `0723IbnFuwati.Hawadith `
    * `0726CallamaHilli.KhulasaAqwal `
    * `0726Yunini.DhaylMiratZaman `
    * `0730MuhammadTujibi.Barnamaj `
    * `0732AbuFida.MukhtasarFiAkhbar `
    * `0732AbuFida.Yawaqit `
    * `0732IbnYacqubJanadi.SulukFiTabaqat `
    * `0733IbnJamaca.Mashyakha `
    * `0733Nuwayri.NihayaArab `
    * `0739SafiDinHanbali.Marasid `
    * `0740IbnDawudHilli.Rijal `
    * `0741KhatibTabrizi.Ikmal `
    * `0742Mizzi.TahdhibKamal `
    * `0747MuhyiDinYunini.Mashyakha `
    * `0748Dhahabi.CibarFiKhabar `
    * `0748Dhahabi.Culuww `
    * `0748Dhahabi.DhaylCibar `
    * `0748Dhahabi.DhaylDiwanDucafa `
    * `0748Dhahabi.DhikrAsmaManTakallama `
    * `0748Dhahabi.DiwanDucafa `
    * `0748Dhahabi.Kashif `
    * `0748Dhahabi.MacrifaQurraKibar `
    * `0748Dhahabi.MizanIctidal `
    * `0748Dhahabi.MucinFiTabaqatMuhaddithin `
    * `0748Dhahabi.MucjamMuhaddithin `
    * `0748Dhahabi.MucjamShuyukh `
    * `0748Dhahabi.MughniFiDucafa `
    * `0748Dhahabi.MukhtasarCuluww `
    * `0748Dhahabi.MukhtasarMinDubaythi `
    * `0748Dhahabi.Muqtana `
    * `0748Dhahabi.RuwatThiqat `
    * `0748Dhahabi.SiyarAclamNubala `
    * `0748Dhahabi.TadhkiraHuffaz `
    * `0748Dhahabi.TarikhIslam `
    * `0748IbnDimyati.Mustafad `
    * `0749IbnWardi.KharidaCajaib `
    * `0749IbnWardi.Tarikh `
    * `0749ShihabDinCumari.MasalikAbsar `
    * `0749Wadiashi.Barnamaj `
    * `0750AbuHafsQazwini.Mashyakha `
    * `0751IbnQayyimJawziyya.IghathaLahfan `
    * `0761IbnKaykaldi.JamicTahsil `
    * `0761IbnKaykaldi.Mukhtalitin `
    * `0762MughaltayIbnQalij.IkmalTahdhib `
    * `0764IbnShakirKutubi.FawatWafayat `
    * `0764Safadi.AcyanCasr `
    * `0764Safadi.NaktHimyan `
    * `0764Safadi.WafiBiWafayat `
    * `0765AbuMahasinHusayni.DhaylTadhkira `
    * `0765AbuMahasinHusayni.IkmalLiRijal `
    * `0767Balawi.TajMafriq `
    * `0768Yafici.MiratJanan `
    * `0771Subki.MucjamShuyukh `
    * `0771Subki.TabaqatShaficiyaKubra `
    * `0774IbnKathir.Bidaya `
    * `0774IbnKathir.TabaqatShaficiyyin `
    * `0774IbnKathir.Takmil `
    * `0774IbnRaficSallami.MashyakhaBayani `
    * `0774IbnRaficSallami.Wafayat `
    * `0775IbnAbiWafa.JawahirMudiya `
    * `0776LisanDinIbnKhatib.Ihata `
    * `0776LisanDinIbnKhatib.KatibaKamina `
    * `0776LisanDinIbnKhatib.KhatraTayf `
    * `0776LisanDinIbnKhatib.MicyarIkhtiyar `
    * `0776LisanDinIbnKhatib.NafadaJirab `
    * `0779IbnBattuta.Rihla `
    * `0782IbnSallar.TabaqatQurra `
    * `0793AbuHasanMalaqi.TarikhQudat `
    * `0795IbnRajabHanbali.DhaylTabaqatHanabila `
    * `0799IbnFarhun.DibajMudhahhab `

* **0900AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `0804IbnMulaqqin.TabaqatAwliya `
    * `0806IbnHusaynCiraqi.DhaylMizan `
    * `0807IbnAhmarKhazraji.NafhaNisriniyya `
    * `0808IbnKhaldun.Rihla `
    * `0808IbnKhaldun.Tarikh `
    * `0809IbnQunfudh.Wafayat `
    * `0812CaliKhazraji.CuqudLuluiyya `
    * `0816AbuBakrMaraghi.Mashyakha `
    * `0817IbnYacqubFiruzabadi.BulghaFiTarajim `
    * `0821Qalqashandi.NihayaArab `
    * `0821Qalqashandi.QalaidJuman `
    * `0821Qalqashandi.SubhAcsha `
    * `0821ShihabDinQalqashandi.Maathir `
    * `0825IbnQasimSabti.IkhtisarAkhbar `
    * `0826IbnCiraqi.Mudallisin `
    * `0826IbnCiraqi.TuhfaTahsil `
    * `0832AbuTayyibFasi.DhaylTaqyid `
    * `0832AbuTayyibFasi.ShifaGharam `
    * `0833IbnJazari.GhayaNihaya `
    * `0842IbnNasirDinDimashqi.RaddWafir `
    * `0842IbnNasirDinDimashqi.TawdihMushtabih `
    * `0845Maqrizi.Bayan `
    * `0845Maqrizi.IqazHunafa `
    * `0845Maqrizi.Mawaciz `
    * `0845Maqrizi.MukhtasarKamil `
    * `0845Maqrizi.Suluk `
    * `0851IbnQadiShuhba.TabaqatShaficiya `
    * `0852IbnHajarCasqalani.DurarKamina `
    * `0852IbnHajarCasqalani.FathBari `
    * `0852IbnHajarCasqalani.InbaGhumr `
    * `0852IbnHajarCasqalani.IsabaFiTamyiz `
    * `0852IbnHajarCasqalani.ItharBiMacrifa `
    * `0852IbnHajarCasqalani.LisanMizan `
    * `0852IbnHajarCasqalani.MucjamMufahras `
    * `0852IbnHajarCasqalani.NuzhaAlbab `
    * `0852IbnHajarCasqalani.RafcCisr `
    * `0852IbnHajarCasqalani.TabaqatMudallisin `
    * `0852IbnHajarCasqalani.TabsirMuntabih `
    * `0852IbnHajarCasqalani.TacjilManfaca `
    * `0852IbnHajarCasqalani.TacrifAhlTaqbis `
    * `0852IbnHajarCasqalani.TahdhibTahdhib `
    * `0852IbnHajarCasqalani.TaqribTahdhib `
    * `0854IbnCarabshah.CajaibMaqdur `
    * `0854IbnDiyaMakki.TarikhMakka `
    * `0855Cayni.CiqdJuman `
    * `0855Cayni.CumdaQari `
    * `0855Cayni.MaghaniAkhyar `
    * `0862IbnMuhammadMujari.Barnamaj `
    * `0871IbnFahdMakki.LahzAlhaz `
    * `0874IbnTaghribirdi.HawadithDahriya `
    * `0874IbnTaghribirdi.ManhalSafi `
    * `0874IbnTaghribirdi.MawridLatafa `
    * `0874IbnTaghribirdi.NujumZahira `
    * `0879IbnQutlubugha.TajTarajim `
    * `0879IbnQutlubugha.Thiqat `
    * `0884IbnMuflih.MaqsidArshad `
    * `0884SibtIbnCajami.Ightibat `
    * `0884SibtIbnCajami.KashfHathith `
    * `0884SibtIbnCajami.KunuzDhahab `
    * `0884SibtIbnCajami.TabyinLiAsma `
    * `0900AbuCabdAllahHimyari.RawdMictar `

* **1000AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `0902Sakhawi.Buldaniyyat `
    * `0902Sakhawi.DuLamic `
    * `0902Sakhawi.ManhalCadhb `
    * `0902Sakhawi.TuhfaLatifa `
    * `0904Burayhi.TabaqatSulahaYaman `
    * `0905Basrawi.Tarikh `
    * `0909IbnMibradHanbali.BahrDamm `
    * `0909IbnMibradHanbali.MucjamKutub `
    * `0911Samhudi.KhulasaWafaWafa `
    * `0911Samhudi.WafaWafa `
    * `0911Suyuti.AsmaMudallisin `
    * `0911Suyuti.AsmaMukhadramin `
    * `0911Suyuti.BughyaWucat `
    * `0911Suyuti.DhaylTabaqatHuffaz `
    * `0911Suyuti.HusnMuhadara `
    * `0911Suyuti.IscafMubatta `
    * `0911Suyuti.ItmamDiraya `
    * `0911Suyuti.LubbLubab `
    * `0911Suyuti.NazmCiqyan `
    * `0911Suyuti.RihNisrin `
    * `0911Suyuti.Shamarikh `
    * `0911Suyuti.TabaqatHuffaz `
    * `0911Suyuti.TabaqatMufassirin `
    * `0911Suyuti.TarikhKhulafa `
    * `0923IbnCabdAllahKhazraji.KhulasaTahdhib `
    * `0927Culaymi.UnsJalil `
    * `0927Nucaymi.DarisFiMadaris `
    * `0929IbnKayyal.KawakibNayyirat `
    * `0938IbnCaliBalawi.Thabat `
    * `0945ShamsDinDawudi.TabaqatMufassirin `
    * `0953IbnTulun.MufakahaKhillan `
    * `0968Tashkubruizadah.ShaqaiqNucmaniyya `
    * `0973CabdWahhabShacrani.LawaqihAnwar `
    * `0984BardDinGhazzi.MatalicBadriya `

* **1100AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `1010TamimiDari.TabaqatSaniya `
    * `1011SahibMacalim.TahrirTawusi `
    * `1016MuhibbDinHamawi.HadiAzcan `
    * `1037CabdQadirCaydarus.TarikhNurSafir `
    * `1041BurhanDinMaliki.BahjaMahafil `
    * `1041Maqarri.AzharRiyad `
    * `1041Maqarri.NafhTib `
    * `1051Cimadi.RawdaRayya `
    * `1061NajmDinGhazzi.KawakibSaira `
    * `1067HajjiKhalifa.KashfZunun `
    * `1069ShihabDinKhafaji.RayhanaAlibba `
    * `1070MuhammadKibrit.RihlaShita `
    * `1078RiyadZadah.AsmaKutub `
    * `1086IbnCajamiMisri.DhaylLubbLubab `
    * `1089IbnCimad.Shadharat `
    * `1100IbnMuhammadAdnahwi.TabaqatMufassirin `
    * `1100MuhammadItlidi.IclamNas `
    * `1100MustafaTafrishi.NaqdRijal `

* **1200AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `1101MuhammadCaliArdabili.JamicRuwat `
    * `1111MuhammadAminMuhibbi.KhulasaAthr `
    * `1119IbnMacsum.SulafaCasr `
    * `1120CaliKhanMadani.DarajatRafica `
    * `1126MuhammadHanbali.Mashyakha `
    * `1147CabdAllahSancani.TarikhYaman `
    * `1153IbnKannan.YawmiyyatShamiyya `
    * `1172IbnKhalifaMasakini.Fahrasa `
    * `1174AbuBarakatSuwaydi.NafhaMiskiya `
    * `1175AhmadBudayri.HawadithDimashq `
    * `1175MuhammadKarabisi.IklilManhaj `
    * `1187SulaymanMahasini.HululTacab `
    * `1195CabdRahmanAnsari.Tuhfa `

* **1300AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `1206Muradi.SilkDurar `
    * `1212BahrCulum.FawaidRijaliya `
    * `1212BahrCulum.FawaidRijaliya `
    * `1218SalihFulani.QatfThamar `
    * `1232IbnKhatibCumari.RawdaFayha `
    * `1237Jabarti.CajaibAthar `
    * `1246IbnHamadBassam.DurarMafakhir `
    * `1250IbnCaliShaykani.BadrTalic `
    * `1269CabdMalikCasimi.SamtNujum `
    * `1270ShihabDinAlusi.GharaibIghtirab `
    * `1277MuhammadTantawi.NashaNahw `
    * `1286IcjazHusaynKunturi.KashfHajb `

* **1400AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `1307Qannawji.AbjadCulum `
    * `1307Qannawji.HittaFiDhikr `
    * `1307Qannawji.LuqtaCajlan `
    * `1313Barujirdi.Taraif `
    * `1313VanDyck.IktifaQunuc `
    * `1315AbuMacaliKalbasi.RasailRijaliyya `
    * `1315Salawi.IstiqsaLiAhkbar `
    * `1318MuhammadSanusi.Musamarat `
    * `1330IbnMusaTabrizi.MiratKutub `
    * `1332ZaynabFawwaz.DurrManthur `
    * `1335CabdRazzaqBaytar.HilyaBashar `
    * `1338MuhammadFaridBey.Bahja `
    * `1338MuhammadFaridBey.Tarikh `
    * `1339IsmacilBashaBaghdadi.HadiyaCarifin `
    * `1339IsmacilBashaBaghdadi.IdahMaknun `
    * `1341CabdHayyTalibi.IclamBiMan `
    * `1345IbnJacfarKattani.RisalaMustatrafa `
    * `1346CbdQadirBadran.Munadama `
    * `1347BashirYamut.Shacirat `
    * `1351IbnHusaynGhazzi.NahrDhahab `
    * `1351YusufIlyanSarkis.MucjamMatbucat `
    * `1354HasanSadr.Takmila `
    * `1355AhmadTahtawi.TanbihWaIqaz `
    * `1356AbuHudaKalbasi.SamaMaqal `
    * `1359CabbasQummi.Kuna `
    * `1360IbnQasimMakhluf.ShajaraNur `
    * `1364IbnHamdMughiri.MuntakhabQabail `
    * `1368HasanAmin.MustadrakatAcyanShica `
    * `1371MuhsinCamili.AcyanShica `
    * `1372KurdCali.KhitatSham `
    * `1381MuhammadSancani.MulhaqBadr `
    * `1383CadbHayyKattani.FihrisFaharis `
    * `1389AghaBuzurgTihrani.DharicaFiTasanifShica `
    * `1389AghaBuzurgTihrani.DhaylKashfZunun `
    * `1389AghaBuzurgTihrani.TASHAnwarSatica `
    * `1389AghaBuzurgTihrani.TASHNawabighRuwat `
    * `1396KhayrDinZirikli.Aclam `

* **1500AH [[ [Re]generated on 2016-08-18 (13:40:01) ]]**

    * `1405CaliShahrudi.Mustadrakat `
    * `1408CumarKahhala.MucjamMuallifin `
    * `1408CumarKahhala.MucjamQabail `
    * `1411SayyidKhui.MucjamRijal `
    * `1411SayyidMarcashi.SharhIhqaq `
    * `1414SalimIbadi.IscafAcyan `
    * `1418SalihAhmadArkani.TihfaMajalis `
    * `1419MahmudTanahi.MujizFiMarajic `
    * `1421HamdJasir.MucjamQabailMCS `
    * `1422MuhammadSalimMuhaysin.MucjamHuffazQuran `
    * `1429BakrIbnCabdAllah.TabaqatNassabin `
    * `1450AkramFaluji.MucjamSaghir `
    * `1450CabdRahmanAlShaykh.Mashahir `
    * `1450MuhammadHadiAmini.MucjamMatbicatNajafiya `
    * `1450MuhammadKhayrRamadan.TakmilaMucjamMuallifin `
    * `1450MuhammadSancani.NaylWatar `
