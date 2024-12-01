# Create your first Android App
* Codelab [here](https://developer.android.com/codelabs/basic-android-kotlin-compose-first-app#0)
  * old legacy code [here](https://github.com/google-developer-training/basic-android-kotlin-compose-birthday-card-app)
* goal
  * create Android App /
    * -- via -- Android Studio empty template
    * use Kotlin & Jetpack Compose

## Requirements
* install [Android Studio](https://developer.android.com/studio)

## How has it been created?
* Follow [this guide](https://developer.android.com/codelabs/basic-android-kotlin-compose-first-app#1)
  * from Android Studio via "Empty" template

## Notes
* Composable functions
  * := functions / marked with `@Composable`
    * uses
      * `setContent()`
      * other composable functions
    * 👀-> tell Kotlin compiler / function will be used by JetPack Compose -- to generate -- UI 👀
    * ⚠️name is capitalized ⚠️
    * return NOTHING
  * preview of the composable
    * WITHOUT building your entire app 
    * annotate with `@Preview`
* `Surface`
  * == container / == section of UI
* if you want to wrap -> use shortcuts
  * | Windows, Alt+Enter
  * | Mac, Option+Enter
* `Modifier`
  * allows
    * augmenting or decorating a composable
