# Perfect Tune Library
Android Library generate simple audio tune of different frequency with no sweat.
generating audio tune is not that easy. This library will help you.

### Installation
Add `maven { url "https://jitpack.io" }` in your root build.gradle

```sh
allprojects {
    repositories {
        jcenter()
        maven { url "https://jitpack.io" }
    }
}
```

Then add the library by including it in one of your dependencies

```sh
dependencies {
    compile 'com.github.karlotoy:perfectTune:1.0.0'
}
```

### Usage

Instantiate the PerfectTune object

```sh
PerfectTune perfectTune = new PerfectTune();
```

set your desired frequency
```sh
perfectTune.setTuneFreq(1108.73D);
```
note: default frequency is 440hz

Start/Stop the tune by

```sh
//start the tune
perfectTune.start();
//stops the tune
perfectTune.stopTune();
```

Have fun in creating tunes :)
