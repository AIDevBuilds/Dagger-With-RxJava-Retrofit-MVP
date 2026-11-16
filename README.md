# Dagger with RxJava, Retrofit and MVP (Android)

Android sample that structures the Dagger, RxJava and Retrofit setup with the Model-View-Presenter pattern.

This is an older sample kept for reference. It is not actively maintained.

## What it shows

- `BasePresenter`, `BaseView` and `BaseFragment` as the MVP base classes
- A `TestFragment`, `TestPresenter` and `TestView` for one screen
- `PresenterComponent` with `ContextModule` and `NetworkModule`, and `@PerActivity` and `@PerFragment` scopes
- Posts loaded from [JSONPlaceholder](https://jsonplaceholder.typicode.com) with Retrofit and RxJava 2

## Stack

Java, Dagger 2.14.1, RxJava 2.1.9, RxAndroid 2.0.2, Retrofit 2.3.0, `minSdkVersion 15`, `compileSdkVersion 27`.

## Run

Open the project in Android Studio and run the `app` module. It uses an older Android Gradle plugin (3.1.x) and `compileSdkVersion 27`, so Android Studio may ask you to update the Gradle wrapper and plugin.

## License

MIT. See [LICENSE](LICENSE).
