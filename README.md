# JAudioTagger

> [!IMPORTANT]
> This project is a fork designed specifically for the [Booming Music](https://github.com/mardous/BoomingMusic) project.
> There are no guarantees that it will work or suit the needs of other projects.

**JAudioTagger** is a Java API for audio metatagging. Both a common API and format
specific APIs are available, currently supports reading and writing metadata for:

- Mp3
- Flac
- OggVorbis
- Mp4
- Mp4 - DASH
- Aiff
- Wav
- Wma
- Dsf
- Opus

### Using

Just add this as a Jitpack dependency:

```
repositories {
    maven { url "https://jitpack.io" }
}

dependencies {
    implementation 'com.github.mardous:jaudiotagger:2.3.14'
}
```

### Requirements

*JAudioTagger* requires Java 1.8 for a full build and install

### Under source control

- `src`                  : source code directory
- `srctest`              : source test code directory
- `www`                  : java doc directory
- `testdata`             : test files for use by the junit tests, not all tests are included in the distribution because of copyright
- `target`               : contains the `jaudiotagger***.jar` built from maven

### License

- `license.txt` : license file
 
 
