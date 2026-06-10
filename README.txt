Solo Leveling Tracker — Projet Android APK-ready
=================================================

Ce ZIP contient un projet Android Studio complet en Kotlin + WebView, prêt à être ouvert et compilé pour Samsung Android.

Prérequis
---------
- Android Studio récent
- SDK Android 34
- JDK 17 (généralement inclus dans Android Studio)

Compilation simple
------------------
1. Décompresse le ZIP.
2. Ouvre Android Studio.
3. Choisis Open et sélectionne le dossier `solo_leveling_tracker_android`.
4. Attends la synchronisation Gradle.
5. Pour installer sur ton Samsung : branche le téléphone en USB + active le débogage USB, puis Run.
6. Pour générer un APK : Build > Build Bundle(s) / APK(s) > Build APK(s).

APK signé (installation propre)
-------------------------------
Build > Generate Signed Bundle / APK > APK > crée une keystore > release.

Remarque
--------
Je ne peux pas compiler l'APK final ici (pas d'Android SDK complet dans ce sandbox), mais le projet est prêt à être ouvert dans Android Studio et compilé en quelques clics.
