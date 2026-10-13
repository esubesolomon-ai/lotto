# Ethio Lottery Demo (Android)

A native Android starter project written in Kotlin and Jetpack Compose.

## Included
- Daily draw: 100 ETB
- Weekly draw: 50 ETB
- Monthly draw: 50 ETB
- Six-digit manual number selection with leading zeros
- Random number generator that avoids numbers already held in this local session
- Simulated ticket purchases only; no real payments
- Independent rolling countdown for each draw type
- My Tickets screen
- Results screen with SHA-256 proof strings for demo results
- Admin demo screen to publish sample results
- Dark navy and gold interface

## Important demo limitations
- Tickets/results are kept in memory and reset when the app process closes.
- This is a single-device demo. It does NOT prevent two different phones from buying the same number.
- Countdown timers are rolling demo timers, not official draw schedules.
- The result hash is illustrative only; the random result is not independently audited or provably fair.
- Admin mode has no login and must not be used in production.
- No real payment, cash prize, or lottery operation is implemented.

## Build
1. Open this folder in Android Studio (recent version).
2. Let Gradle sync and install the Android SDK platform/build tools if prompted.
3. Run the `app` configuration on an emulator or connected Android phone.
4. To create an APK, use **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

A real launch requires legal/licensing review, age and location controls as appropriate, secure authentication, server-side transactional number reservation, a persistent database, auditable draw generation, and compliant payment integration.
