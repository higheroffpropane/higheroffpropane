<p align="center"><img src="./assets/mobile.svg" width="100%" alt="Dmitry Skochilov · Mobile developer · Android, Kotlin Multiplatform and Flutter"></p>

I build and maintain mobile apps. Over two years in commercial Android development, I built a marketplace module and QR guest passes for a residential services app used in seven cities. I also study information security, with a focus on mobile AppSec.

### Technical stack

| Area | Tools and techniques |
| --- | --- |
| Native Android | Kotlin, Android SDK, Jetpack Compose, Material 3, Navigation, ViewModel, WorkManager |
| Kotlin Multiplatform | Shared Kotlin business logic, common and platform-specific source sets, platform implementations |
| Flutter | Dart, widget composition, navigation, asynchronous API calls and UI state management |
| Architecture | MVVM and MVP in existing apps, MVI with unidirectional data flow, feature modules, repository interfaces, dependency injection with Hilt and Koin |
| Data and concurrency | Coroutines, Flow, StateFlow, RxJava, REST APIs, Retrofit, OkHttp, Ktor, kotlinx.serialization |
| Local storage | Room, Paging 3 with RemoteMediator, Preferences DataStore, Coil image caching |
| Testing and delivery | JUnit, Espresso, Compose UI tests, Git, Gradle Kotlin DSL, GitHub Actions, Android lint, detekt and ktlint |

### Selected projects

| Project | Implementation | Code to explore |
| --- | --- | --- |
| [EasyDinner](https://github.com/higheroffpropane/easydinner) | A Compose client sends ingredients and cooking preferences to a Ktor server. The client and server use the same Kotlin request and response types. | [Shared API contract](https://github.com/higheroffpropane/easydinner/tree/master/shared) · [Recipe providers](https://github.com/higheroffpropane/easydinner/tree/master/server/src/main/kotlin/com/dskochilov/easydinner/server/recipe) |
| [Cosmos](https://github.com/higheroffpropane/cosmos) | A NASA photo explorer with a Room-backed rover gallery. Media search uses Flow to debounce input and cancel superseded queries. | [Rover pagination](https://github.com/higheroffpropane/cosmos/blob/main/core/data/src/main/kotlin/com/dskochilov/cosmos/core/data/mars/MarsPhotoRemoteMediator.kt) · [Search state](https://github.com/higheroffpropane/cosmos/blob/main/feature/search/src/main/kotlin/com/dskochilov/cosmos/feature/search/SearchViewModel.kt) |

### Freelance work

- **Feature development** — implement Compose screens and connect them to existing REST APIs and SDKs.
- **App maintenance** — trace crashes and state bugs in Kotlin or RxJava code, fix the cause and add regression coverage.
- **Release support** — troubleshoot Gradle builds, run UI checks and verify fixes on devices.

**Contact** · [Telegram @higheroffpropane](https://t.me/higheroffpropane) · Russian and English (B2)
