# LQ Cyber - App ya Android

Tovuti ya LQ Cyber (folda `www/`) ikiwa imefungwa kama app ya Android kwa kutumia Capacitor.
APK inajengwa na GitHub Actions, huhitaji Android Studio.

## Hatua za kupata APK

1. Fungua akaunti ya GitHub, tengeneza repository mpya (mfano `lq-cyber-app`).
2. Pakia **vitu vyote vya folda hii** kwenye repository, pamoja na folda `www` na `.github`.
   Hakikisha njia ya faili ni `.github/workflows/android.yml`.
3. Nenda kwenye kichupo cha **Actions**, chagua **Jenga APK ya Android**, bonyeza **Run workflow**
   (au itaanza yenyewe ukipakia kwenye tawi la `main`).
4. Subiri dakika 5 hadi 10. Ukimaliza, fungua kazi hiyo, chini kuna **Artifacts**, pakua **LQ-Cyber-APK**.
5. Toa faili la `app-debug.apk` kwenye zip, ulitume kwenye simu na usakinishe.
   Android itakuomba kuruhusu "kusakinisha kutoka vyanzo visivyojulikana".

## Kubadilisha tovuti

Hariri mafaili ndani ya `www/`, kisha pakia tena kwenye GitHub. APK mpya itajengwa.

## Muhimu

- Hii ni APK ya **debug**, inafaa kwa kusambaza na kujaribu. Kwa Google Play unahitaji
  APK/AAB ya **release** iliyosainiwa (signed), hatua nyingine.
- Ikoni ni ile ya kawaida ya Capacitor mpaka utakapotengeneza ikoni ya PNG ya nembo yako.
- Fonti na tovuti zinahitaji mtandao ili zionekane kikamilifu.
