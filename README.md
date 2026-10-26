```markdown
# Workshop-Android

**A standard software project.**

**Installation:**

1.  Clone the repository: `git clone https://github.com/your-username/workshop-android`
2.  Navigate to the project directory: `cd workshop-android`
3.  Dependencies are resolved automatically by Gradle on the first build (`./gradlew dependencies` lists them).
4.  Run `./gradlew assembleDebug` to build the debug APK.

**Usage:**

*   **Building:**  `./gradlew assembleDebug` (Build the debug APK)
*   **Running:** `./gradlew installDebug` (Install the app on a connected device or emulator, then launch it from the device)
*   **Testing:** `./gradlew test` (Run local unit tests)
*   **Instrumented tests:** `./gradlew connectedAndroidTest` (Run tests on a device or emulator)
*   **Analyzing:** `./gradlew lint` (Run Android lint)
*   **Configuration:**  `settings.gradle` (Configure project settings)
*   **Gradle Configuration:** `gradle.properties` (Specify Gradle settings)
*   **Gradle Wrapper (Windows):** `gradlew.bat` (Run Gradle for local compilation)
*   **Renovation:** `renovate.json` (Update the project)
*   **Settings:** `settings.gradle` (Define project-specific settings)

**Files:**

*   `.gitignore`
*   `.idea`
*   app
*   build.gradle
*   gradle.properties
*   gradle
*   gradlew
*   gradlew.bat
*   renovate.json
*   settings.gradle
```