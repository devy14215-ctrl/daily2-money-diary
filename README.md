# Shailu Bhai — Daily Collection (Android APK)

Web app `app/src/main/assets/index.html` ko WebView me chalata hai. Har GitHub push par APK auto-build hota hai.

## APK kaise banaye
1. GitHub par NAYA **private** repository banao.
2. Is folder ki saari files upload karo (hidden folder `.github` bhi — uske bina APK build nahi hoga).
3. Repo > **Actions** tab > "Build APK" chalne do (5-8 min).
4. Complete hone par: **Releases** (right side) me `ShailuBhai.apk`, ya run ke andar **Artifacts**.
5. APK phone me install karo (Unknown sources allow karna padega).

## Zaruri baatein
- Repo private rakho — `app/shailu-release.keystore` signing key isi me hai.
- Naya APK purane ke upar install karo (uninstall mat karo) — data safe rahega.
- Uninstall karne se app ka data mit jata hai. Pehle **Settings > Export JSON Backup** karo.
- Chrome ka data APK me apne aap nahi aata: Chrome me Export Backup, APK me Restore.
- App update: `index.html` badlo, commit karo, naya APK auto-ban jayega.
