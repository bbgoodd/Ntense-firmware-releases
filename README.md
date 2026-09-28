# Ntense firmware releases

Public firmware distribution for Ntense-N1. App, firmware and hardware sources
are maintained separately in private repositories.

Install compatible updates through the Ntense app after connecting to your device.
Keep the device powered and the app open until the firmware self-test is confirmed.
Older devices may require a one-time USB service update before BLE OTA is supported.

Release tags use `firmware/v<semantic-version>`. Each published release contains
`manifest.json`, explicitly supported hardware images, and third-party notices.
The app selects the newest compatible stable firmware for the connected hardware,
which may differ from the most recently published release. Prereleases are not
offered by the stable app.

Board ID: `Ntense-N1`. Supported revision identifiers: `N1`, `N1_legacy`.
Manifest schema: 1. BLE OTA protocol: 2. SHA-256 verifies file integrity; it is not
a firmware signature or a proof of origin. Do not flash images for another revision.
