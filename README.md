# JARVIS Reply Helper — starter Android project

This is a starter project, not a finished AI app. It contains:
- A basic Android screen where the user pastes chat text and gets simple offline reply suggestions.
- An optional floating "J" bubble that opens the app.
- A GitHub Actions workflow that builds a debug APK and uploads it as an artifact.

## Important limitations
- It does NOT log into Instagram or automatically read private DMs.
- It does NOT call an AI model; suggestions are simple offline rules.
- The floating bubble only opens this helper app; it does not inspect Instagram's screen.
- The debug APK is not signed for Play Store release.
- Review and test before installing. Only grant overlay permission if you trust the app.

## Build APK using GitHub Actions
1. Create a new GitHub repository and upload the contents of this ZIP.
2. Open the repository's Actions tab.
3. Run "Build Android APK" (or push to the main branch).
4. Open the completed workflow run and download the `jarvis-instagram-debug-apk` artifact.
5. Extract the artifact ZIP to get `app-debug.apk`.
