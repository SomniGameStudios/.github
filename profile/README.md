# SomniGameStudios

We're building **[Stepland](https://stepland.es)** – a gamified healthy habits mobile game where your real-world physical activity brings a virtual village to life.

Built with the [Godot Engine](https://godotengine.org) for Android and iOS.

---

## 🚀 Our Mission

We build longevity apps and games designed to help people live longer and better.

Our long-term vision is bold:  
To contribute to a future where humans can live 150 years with a biological age of 30.

We believe this future won't be built only in laboratories.  
It will be built in daily habits: movement, sleep, nutrition, mental health, hydration, and social connection.

Healthy habits are the operating system of biological age.  
Our job is to turn them into something people actually want to repeat.

Stepland is how we bring this mission to life – a live-ops mobile game powered by Godot.

Mobile live games require serious infrastructure: authentication, payments, ads, analytics, health data, notifications, and more.  
In the Godot ecosystem, some of these tools exist. Some are incomplete. Some don't exist at all.

So we build them – and we open-source them.

In short, we exist to:

- Make healthy habits feel like a game  
- Ship production-ready mobile games with Godot  
- Strengthen the Godot mobile ecosystem  
- Share what we build with the community

If we need it and it doesn't exist, we build it – and share it.

---

## 🔌 Mobile Integrations

Shipping a real mobile game means real mobile infrastructure.

Here's what powers Stepland:

- **Backend** – Firebase + [PlayFab](https://github.com/Structed/godot-playfab)
- **Authentication** – Firebase ([godot-firebase-ios](https://github.com/SomniGameStudios/godot-firebase-ios) for iOS, [GodotFirebaseAndroid](https://github.com/syntaxerror247/GodotFirebaseAndroid) for Android)
- **Push Notifications** – Firebase ([godot-firebase-ios](https://github.com/SomniGameStudios/godot-firebase-ios) for iOS, [GodotFirebaseAndroid](https://github.com/syntaxerror247/GodotFirebaseAndroid) for Android)
- **IAPs & Subscriptions** – [godot-google-play-billing](https://github.com/godot-sdk-integrations/godot-google-play-billing) (Android), StoreKit2 (iOS), RevenueCat
- **In-App Ads** – [godot-admob-plugin](https://github.com/poingstudios/godot-admob-plugin)
- **Crash Reporting** – [Sentry](https://docs.sentry.io/platforms/godot/) (planned)
- **Attribution / MMP** – TBD
- **Social Features** – TBD
- **Analytics** – [ByteBrew](https://bytebrew.io)
- **Health Data** – Custom Android plugin + [HealthKit](https://github.com/slowestmonkey/godot-healthkit-plugin) (iOS)
- **Testing** – [GdUnit4](https://github.com/MikeSchulze/gdUnit4)
- **Static Testing** – [godot-gdscript-toolkit](https://github.com/SomniGameStudios/godot-gdscript-toolkit)
- **CI/CD** – GitHub Actions

Many of the bridges between Godot and these native services are being developed right here.

---

## 📦 Public Repositories

These are some of the integrations we're actively building and maintaining:

- [godot-firebase-ios](https://github.com/SomniGameStudios/godot-firebase-ios) – Firebase integration for Godot iOS
- [GodotFirebaseAndroid](https://github.com/syntaxerror247/GodotFirebaseAndroid) – Firebase integration for Godot Android
- [godot-facebook-sdk-android](https://github.com/SomniGameStudios/godot-facebook-sdk-android) – Facebook SDK integration for Godot Android
- [godot-admob-plugin](https://github.com/poingstudios/godot-admob-plugin) – AdMob integration for Godot
- [godot-gdscript-toolkit](https://github.com/SomniGameStudios/godot-gdscript-toolkit) – Static testing toolkit for Godot GDScript

More coming as Stepland grows.

---

## 🌱 Growing Godot for Mobile

Godot is an incredible engine, but mobile live-ops games push its ecosystem further.

We're committed to:

- Expanding native mobile capabilities  
- Sharing production-tested integrations  
- Demonstrating that Godot can power serious mobile games  
- Contributing back to open source

If you're building mobile games with Godot, let's grow this ecosystem together.
