# SMS Gateway: Android app

  Turns an Android phone into an SMS gateway for your
  [SMS Gateway](https://app.tritech-server.site) account. Not on Google Play.

  ## Install
  1. Download the latest APK from **Releases**, or scan the QR code at
     https://app.tritech-server.site/download
  2. Allow installs from your browser when Android asks.
  3. Open the app → **Scan pairing QR** → scan the code from
     Dashboard → Devices → Add phone.

  ## Verify the download
  Every release is signed with the same key. Before installing, you can check:

  | Version | SHA-256 of the APK |
  |---|---|
  | 1.1.0 | `7e3eaf7b92f8efcea0b2370c36296a7f5153f1ebb6b10b9d91b0d0c413947bb3` |

  Signing certificate SHA-256 (all releases):
  `c97283da438359e4834fea6dcba9b893dd63f3beeb6d488074b021cd7a252591`

      shasum -a 256 sms-gateway-1.1.0.apk
      apksigner verify --print-certs sms-gateway-1.1.0.apk

  This repository contains release files only. There is no source code here.
