# Weather Live Galaxy configuration (integration in progress)

This configuration is reserved for package `apps.channelsapp.rateweather.samsungapps.com`.
The Samsung IAP product list is empty until products are registered for this package.

**Important:** At present no released or test APK is wired to this file. Editing
it does not yet control advertisements or purchases. Interval values are initial
configuration candidates and must be verified against actual placement behavior.
The AdMob app ID remains in the Android manifest and is not remotely changeable.
Do not put passwords, API keys, or other secrets in this public repository.

After app integration, validate remote changes, last-known-good/offline behavior,
consent and premium gating, stale ad cache disposal, and separate Samsung receipt
verification and restore. Never grant premium solely from remote configuration.
