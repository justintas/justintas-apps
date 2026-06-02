# justintas-apps

iOS applications by Justin Tew. This repository hosts the public-facing pages (landing, privacy policies) for all apps.

## Apps

### StepMeterX
Step counter with GPS route tracking and walking history. All data stored locally on your device.
- **Privacy Policy:** [stepmeter/](stepmeter/)

### Numinion
Professional calculator with graphing, RPN mode, unit converter, and custom programs. Scientific and financial calculations, offline.
- **Privacy Policy:** [numina/](numina/)

### Cukup
Budget Survival Tracker — see your daily spending allowance at a glance. Track expenses, subscriptions, multiple income sources.
- **Privacy Policy:** [cukup/](cukup/)

### Gyro Dash
Tilt-controlled arcade racer — dodge obstacles, collect coins, and unlock vehicles using your phone's gyroscope. Free with ads, or go ad-free with an in-app purchase.
- **Privacy Policy:** [gyrodash/](gyrodash/)

### SliceStackX
One-tap tower builder — tap to drop, slice off the overhang, and chase the satisfying "Perfect" snap. Free with ads, or unlock Remove Ads and The Gold Tower skin via in-app purchase.
- **Privacy Policy:** [slicestackx/](slicestackx/)

### DailyThreeX
Habit tracker built around a single constraint: track exactly three habits at a time. One-tap check-in, perfect-day streaks, and a daily reminder that auto-skips when you've already finished. Premium unlocks dark mode, custom app icons, unlimited history, and PDF export. One-time purchase, no subscription.
- **Privacy Policy:** [dailythreex/](dailythreex/)

### StorageXSense
Duplicate cleaner — finds duplicate photos, large videos, and duplicate contacts, then helps you delete or merge them to reclaim space. All scanning happens on-device; nothing is ever uploaded. Pro unlocks deletion, contact merge, Light/Dark mode, and custom app icons. One-time purchase, no subscription.
- **Privacy Policy:** [storagesense/](storagesense/)

## Privacy Commitment

All apps in this suite:
- ✅ Store all game/app data locally on your device only
- ✅ No user accounts or cloud sync
- ✅ No analytics or crash reporting

**Gyro Dash** and **SliceStackX** additionally use Google AdMob for advertising. AdMob may collect advertising identifiers and device info to serve relevant ads. See the [Gyro Dash](gyrodash/) and [SliceStackX](slicestackx/) privacy policies for full details. Ad-free play is available via in-app purchase.

Each app has a detailed privacy policy in its folder.

## Building

Apps are built with:
- **StepMeterX:** SwiftUI, HealthKit, CoreLocation
- **Numinion:** SwiftUI, Swift Charts
- **Cukup:** SwiftUI, SwiftData, StoreKit 2
- **Gyro Dash:** HTML5/JS (WKWebView), CoreMotion, Google Mobile Ads SDK, StoreKit 2
- **SliceStackX:** SwiftUI, SpriteKit, Google Mobile Ads SDK, StoreKit 2
- **DailyThreeX:** SwiftUI, SwiftData, StoreKit 2, UserNotifications
- **StorageXSense:** SwiftUI, Photos, Contacts, StoreKit 2, LocalAuthentication

Most apps target iOS 17+; StorageXSense targets iOS 16+; SliceStackX targets iOS 15+.

## Support

Questions about privacy or the apps? Reach out to [justintas@gmail.com](mailto:justintas@gmail.com).

---

© 2026 Justin Tew. All rights reserved.
