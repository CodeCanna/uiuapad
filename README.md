**Uiuapad?**

Uiuapad is an idea for an android app to edit and run Uiua code natively on Android.

**Critical Features**

* The ability to create, edit, and compile Uiua code natively
* The ability to type Uiua code using an in-app Uiua keyboard
* A saving feature allowing the user to save Uiua source files to the android filesystem
* Uiua has a module system allowing us to bring in Uiua code from others, we need a way to manage Uiua projects on android

**How can this be accomplished?**

Google offers a [library](https://source.android.com/docs/setup/build/rust/building-rust-modules/overview) to compile and run Rust natively on Android.  Uiua is written in Rust so it should be possible to run the Uiua compiler directly in Android.
This is a pretty big undertaking, and I'm going to do my best to bring this to fruition because I want this to exist.  If this feels like something you want to exist consider helping with development.
Uiua has 116 glyphs, they keyboard will need to be carefully designed.

**Contribution Rules**

* Keep to Android and Rust coding conventions as much as possible
* Be kind and courteous

