# justintas-apps

iOS applications by Justin Tew. This repository hosts the public-facing pages (landing, privacy policies) for all apps.

## Apps

### StepMeter
Step counter with GPS route tracking and walking history. All data stored locally on your device.
- **Privacy Policy:** [stepmeter/](stepmeter/)

### Numina
Professional calculator with graphing, RPN mode, unit converter, and custom programs. Scientific and financial calculations, offline.
- **Privacy Policy:** [numina/](numina/)

### Cukup
Budget Survival Tracker — see your daily spending allowance at a glance. Track expenses, subscriptions, multiple income sources.
- **Privacy Policy:** [cukup/](cukup/)

### Gyro Dash
Tilt-controlled arcade racer — dodge obstacles, collect coins, and unlock vehicles using your phone's gyroscope. Free with ads, or go ad-free with an in-app purchase.
- **Privacy Policy:** [gyrodash/](gyrodash/)

### SliceStack
One-tap tower builder — tap to drop, slice off the overhang, and chase the satisfying "Perfect" snap. Free with ads, or go ad-free with an in-app purchase.
- **Privacy Policy:** [slicestack/](slicestack/)

## Privacy Commitment

All apps in this suite:
- ✅ Store all game/app data locally on your device only
- ✅ No user accounts or cloud sync
- ✅ No analytics or crash reporting

**Gyro Dash** and **SliceStack** additionally use Google AdMob for advertising. AdMob may collect advertising identifiers and device info to serve relevant ads. See the [Gyro Dash](gyrodash/) and [SliceStack](slicestack/) privacy policies for full details. Ad-free play is available via in-app purchase.

Each app has a detailed privacy policy in its folder.

## Building

Apps are built with:
- **StepMeter:** SwiftUI, HealthKit, CoreLocation
- **Numina:** SwiftUI, Swift Charts
- **Cukup:** SwiftUI, SwiftData, StoreKit 2
- **Gyro Dash:** HTML5/JS (WKWebView), CoreMotion, Google Mobile Ads SDK, StoreKit 2
- **SliceStack:** SwiftUI, SpriteKit, Google Mobile Ads SDK, StoreKit 2

Most apps target iOS 17+; SliceStack targets iOS 15+.

## Support

Questions about privacy or the apps? Reach out to [justintas@gmail.com](mailto:justintas@gmail.com).

---

© 2026 Justin Tew. All rights reserved.
