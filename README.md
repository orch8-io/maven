# Orch8 Maven Repository

Public, read-only Maven repository for released Orch8 Android SDK artifacts.

```kotlin
repositories {
    maven("https://raw.githubusercontent.com/orch8-io/maven/main")
}

dependencies {
    implementation("io.orch8:orch8-mobile:0.7.0")
}
```

Artifacts are copied byte-for-byte from signed Orch8 Engine GitHub releases.
