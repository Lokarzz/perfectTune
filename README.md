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
    implementation 'com.github.karlotoy:perfectTune:1.0.3'
}
```

### Usage

Instantiate the PerfectTune object

```sh
PerfectTune perfectTune = new PerfectTune();
```

set your desired frequency
```sh
perfectTune.setTuneFreq(freq in hz);
```

set the amplitude (default 10000)
```java
perfectTune.setAmplitude(amp);
```

Start/Stop the tune by
```sh
//start the tune
perfectTune.playTune();
//stops the tune
perfectTune.stopTune();
```

Have fun in creating tunes :)
