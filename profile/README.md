# SomniGameStudios

We're building **[Stepland](https://stepland.es)** — a gamified healthy habits mobile game where your real-world physical activity brings a virtual village to life.

Built with the [Godot Engine](https://godotengine.org/) for Android and iOS.

---

## 🚀 Our Mission

We believe **healthy habits should feel like a game**.

Stepland is a live-ops mobile game — and mobile games require deep platform integrations: authentication, payments, ads, analytics, attribution, health data, notifications, and more.

In the Godot ecosystem, some of these integrations exist.
Some are incomplete.
Some don't exist at all.

So we're building them.

And when we do, we **open-source them**.

Our goal is not only to ship Stepland — but to:

- Strengthen the Godot mobile ecosystem
- Prove that Godot is production-ready for mobile live-ops games
- Help other developers ship faster
- Contribute back to the community

If we need it and it doesn't exist, we build it — and share it.

---

## 🔌 Mobile Integrations

Shipping a real mobile game means real mobile infrastructure.

Here's what powers Stepland:

- **Backend** — [Firebase](https://github.com/SomniGameStudios/firebase-mobile-integration-demo) + [PlayFab](https://github.com/Structed/godot-playfab)
- **Authentication** — Firebase ([firebase-mobile-integration-demo](https://github.com/SomniGameStudios/firebase-mobile-integration-demo))
- **Push Notifications** — Firebase Cloud Messaging ([godot-firebase](https://github.com/godot-mobile-plugins/godot-firebase))
- **IAPs & Subscriptions** — [Google Play Billing](https://github.com/godot-sdk-integrations/godot-google-play-billing) (Android), StoreKit2 (iOS), RevenueCat
- **In-App Ads** — [AdMob](https://github.com/godot-sdk-integrations/godot-admob)
- **Crash Reporting** — [Sentry](https://docs.sentry.io/platforms/godot/) (planned)
- **Attribution / MMP** — TBD
- **Social Features** — TBD
- **Analytics** — ByteBrew
- **Health Data** — Custom Android plugin + [HealthKit](https://github.com/slowestmonkey/godot-healthkit-plugin) (iOS)
- **Testing** — [GdUnit4](https://github.com/MikeSchulze/gdUnit4)
- **CI/CD** — GitHub Actions

Many of the bridges between Godot and these native services are being developed right here.

---

## 📦 Public Repositories

These are some of the integrations we're actively building and maintaining:

- [**firebase-mobile-integration-demo**](https://github.com/SomniGameStudios/firebase-mobile-integration-demo) — Firebase Auth integration for Godot (Android & iOS)
- [**godot-facebook-sdk-android**](https://github.com/SomniGameStudios/godot-facebook-sdk-android) — Facebook SDK integration for Godot Android

More coming as Stepland grows.

---

## 🌱 Growing Godot for Mobile

Godot is an incredible engine — but mobile live-ops games push its ecosystem further.

We're committed to:

- Expanding native mobile capabilities
- Sharing production-tested integrations
- Demonstrating that Godot can power serious mobile games
- Contributing back to open source

If you're building mobile games with Godot — let's grow this ecosystem together.
