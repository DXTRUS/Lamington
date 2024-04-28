<div align="center">

## Lamington

[![MIT License](https://img.shields.io/github/license/DXTRUS/Lamington?&logo=github)](LICENSE)

Lamington is a 1.20.4 Purpur fork focusing on making scaling servers a painless experience, whether it be an SMP or skyblock, Lamington will be sure to help your development process smoother!

</div>

## Features
- [HeartBeat](README.md)
- - API for getting information
- - Syncs data between all Lamington instances connected to the same Redis server
- - Use the information outside just your server (ie: Your website)
- [SMP Zoning](SMP-ZONING.md)
- - Split your world across multiple servers
- - Customisable border

## Contact
Join us on Discord: https://discord.gg/RRzCH6WjEv

## API

### [Javadoc](https://maven.asdev.info/javadoc/public/net/dxtrus/lamington/lamington-api/1.20.4-R0.1-SNAPSHOT)

### Dependency Information
Maven
```xml
<repository>
    <id>dxtrus-public</id>
    <url>https://maven.asdev.info/public</url>
</repository>
```
```xml
<dependency>
    <groupId>net.dxtrus.lamington</groupId>
    <artifactId>lamington-api</artifactId>
    <version>1.20.4-R0.1-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
```

Gradle
```kotlin
repositories {
    maven("https://maven.asdev.info/public")
}
```
```kotlin
dependencies {
    compileOnly("net.dxtrus.lamington:lamington-api:1.20.4-R0.1-SNAPSHOT")
}
```

Yes, this also includes all API provided by Purpur, Pufferfish, Paper, Spigot, and Bukkit.

## License
All patches are licensed under the MIT license, unless otherwise noted in the patch headers.

[![MIT License](https://img.shields.io/github/license/PurpurMC/Purpur?&logo=github)](LICENSE)

See [PaperMC/Paper](https://github.com/PaperMC/Paper), and [PaperMC/Paperweight](https://github.com/PaperMC/paperweight) for the license of material used by this project.

## bStats
Still waiting for bstats to give us a server impl id!
//[![bStats Graph Data](https://bstats.org/signatures/server-implementation/Purpur.svg)](https://bstats.org/plugin/server-implementation/Purpur)


## API

Coming Soon!

Yes, this also includes all API provided by Paper, Spigot, and Bukkit.
