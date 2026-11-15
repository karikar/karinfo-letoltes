# KarInfo – letöltés

Időjárás, műholdkép, útviszonyok, áram- és gázrendszer egy képernyőn.

## Letöltés

**[→ A legújabb változatok a Kiadások (Releases) oldalon](../../releases)**

| Változat | Fájl | Rendszer |
|---|---|---|
| Windows – telepítő (ajánlott) | [`KarInfo-telepito-1.18.0.exe`](https://github.com/karikar/karinfo-letoltes/releases/download/windows-v1.18.0/KarInfo-telepito-1.18.0.exe) | 64 bites Windows 10/11 |
| Windows – telepítés nélkül | [`KarInfo-hordozhato-1.18.0.zip`](https://github.com/karikar/karinfo-letoltes/releases/download/windows-v1.18.0/KarInfo-hordozhato-1.18.0.zip) | 64 bites Windows 10/11 |
| Android | [`KarInfo-1.19.apk`](https://github.com/karikar/karinfo-letoltes/releases/download/android-v1.19/KarInfo-1.19.apk) | Android 5.0 vagy újabb |
| Samsung Smart TV | [`KarInfo-tv-1.0.7.wgt`](https://github.com/karikar/karinfo-letoltes/releases/download/tv-v1.0.7/KarInfo-tv-1.0.7.wgt) | Tizen 3.0 vagy újabb (kb. 2017 utáni Samsung tévék) |

A változatok külön kiadásban jelennek meg (`windows-v…`, `android-v…`, `tv-v…`),
ezért a legújabbat mindegyikből a Kiadások listájában érdemes keresni.

## Telepítés

**Windows:** töltsd le és futtasd a telepítőt. Mivel a program nincs digitálisan aláírva,
az első indításkor a Windows figyelmeztethet („A Windows megvédte a számítógépet”) –
ilyenkor *További információ → Futtatás mindenképp*. Frissítéskor elég az új telepítőt
futtatni. A Microsoft Edge WebView2 kell hozzá, ez Windows 10/11-en gyárilag megvan.

**Android:** töltsd le az APK-t a telefonra, és nyisd meg. A telefon rákérdez az
„ismeretlen forrásból származó alkalmazások” engedélyezésére – ezt az adott alkalmazásnál
(pl. Fájlok, Chrome) kell megengedni. Az új verzió frissítésként települ a régi fölé.

> **Samsung telefonon** (One UI 6 / Android 14-től) az **Automatikus blokkoló** bekapcsolva
> nem enged a Galaxy Store-on és a Play Áruházon kívülről alkalmazást telepíteni – így a
> KarInfót sem, és a programon belüli frissítést sem. Telepítés vagy frissítés előtt kapcsold ki:
> *Beállítások → Biztonság és adatvédelem → Automatikus blokkoló*, utána vissza lehet kapcsolni.
> A KarInfo frissítéskor erre figyelmeztet, és egy gombbal megnyitja a beállítást.

**Samsung Smart TV**

**⬇ Közvetlen letöltés: [`KarInfo-tv-1.0.7.wgt`](https://github.com/karikar/karinfo-letoltes/releases/download/tv-v1.0.7/KarInfo-tv-1.0.7.wgt)**

Samsung-tévére az áruházon kívül csak a tévéhez kötött, Samsung-fiókkal
készült aláírással lehet alkalmazást telepíteni. Ezt az ingyenes **Apps2Samsung** program
elvégzi helyetted; kell hozzá egy számítógép (vagy Android-telefon) ugyanazon a hálózaton.

1. **Apps2Samsung letöltése:** <https://github.com/Apps2Samsung/Apps2Samsung/releases/latest>
   – Windowson az `Apps2Samsung-v…-win-x64.msi` (telepítő) vagy az `Apps2Samsung-v…-win-x64.zip`
   (kicsomagolás után az `Apps2Samsung.exe` indítható). Van macOS-, Linux- és Android-változat is.
   A program nincs digitálisan aláírva, ezért a Windows figyelmeztethet: *További információ →
   Futtatás mindenképp*.
2. **Fejlesztői mód a tévén:** a tévén nyisd meg az **Alkalmazások** (Apps) képernyőt, és a
   távirányítón üsd be: **1 2 3 4 5**. A megjelenő ablakban: *Developer mode*: **On**,
   *Host PC IP*: a számítógéped IP-címe (Windowson: `ipconfig` → IPv4-cím). OK, majd indítsd
   újra a tévét (kikapcsolás, utána fél percre áramtalanítás).
3. **Telepítés:** indítsd el az Apps2Samsungot, válaszd ki a tévét, majd a saját `.wgt`
   telepítését, és add meg ezt a közvetlen letöltési linket:
   `https://github.com/karikar/karinfo-letoltes/releases/download/tv-v1.0.7/KarInfo-tv-1.0.7.wgt`
   (vagy töltsd le a fájlt, és válaszd ki a gépről).
4. **Samsung-fiók:** az első telepítéskor a program bekéri a Samsung-fiókodat, és azzal aláírja
   a csomagot a te tévédre. A KarInfo ezután a tévé Alkalmazások listájában marad.

Frissítés: az új verziót ugyanígy kell telepíteni. Ha a KarInfo korábban más aláírással került
fel, előbb töröld a tévéről. Kezelés: nyilak és OK; 1–5: fülek; piros: frissítés, zöld:
helyszín; Vissza kétszer: kilépés.
Az Apps2Samsung közösségi, nem a Samsung által készített program; a KarInfónak nincs köze hozzá.

## Adatforrások

Open-Meteo, HungaroMet (orvosmeteorológia – fronthatás), RainViewer, OpenWeatherMap, Esri,
Útinform, MAVIR, energy-charts.info, netzfrequenz.info, ENTSOG, GIE AGSI+. Az adatok a forrásaik felhasználási feltételei
szerint használhatók.

Ez a tároló csak a kész programokat tartalmazza.
