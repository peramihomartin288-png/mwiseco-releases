# MWISECO Android Releases

Public APK distribution repository for two separate native Android apps.

- Teacher app source: private repository `mwiseco-teachers`.
- Secretary app source: private repository `mwiseco-secretary`.

Each app must use its own Android application ID, versionCode sequence, and permanent signing key. Never replace an installed app with an APK signed by a different key.

## APK asset names
- `mwiseco-teachers-vX.Y.Z.apk`
- `mwiseco-secretary-vX.Y.Z.apk`

## Update manifest
`releases.json` is the public update manifest. Each app reads only its own entry. A release workflow must update the matching entry only after its signed APK has been published successfully.

Do not upload source code, keystores, passwords, privileged API keys, or private school data to this public repository.
