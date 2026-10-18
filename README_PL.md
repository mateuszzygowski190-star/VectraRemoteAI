# Vectra Remote AI — prototyp 0.1

To **projekt APK z interfejsem**, nie działający pilot. Obecnie przyciski jedynie zgłaszają brak transportu.
Brakuje parowania i komunikacji Android TV Remote v2 oraz połączenia GPT Actions.

## Budowanie z telefonu przez GitHub
1. Wgraj **zawartość folderu VectraRemoteAI**, nie sam folder, do głównego katalogu repozytorium. Zachowaj `.github/workflows/android.yml`.
2. Zakładka **Actions → Build Android APK → Run workflow** (lub automatyczny build po push).
3. Po zakończeniu workflow otwórz przebieg i sekcję **Artifacts**, pobierz `VectraRemoteAI-debug-apk`, rozpakuj ZIP i zainstaluj APK na telefonie.
4. To APK sprawdza wyłącznie uruchamianie interfejsu — nie steruje jeszcze dekoderem.

Nie publikuj haseł, kluczy ani kodów parowania.
