# Signs Plugin

![Banner][banner]

<div align="center">

  [![Modrinth][badge-modrinth]][modrinth]
  [![Release][badge-maven-central]][maven-central]
  [![Dev][badge-dev]][dev]
  [![License][badge-license]][license]
  <br>

  [![Discord][badge-discord]][social-discord]
  [![Follow @simplecloudapp][badge-x]][social-x]
  [![Follow @simplecloudapp][badge-youtube]][social-youtube]
  <br>

  [Report a Bug][issue-bug-report]
  ·
  [Request a Feature][issue-feature-request]
  <br>

🌟 Give us a star — your support means the world to us!
</div>
<br>

> All information about this project can be found in our detailed [documentation][docs-thisproject].

The Signs Plugin is an intuitive tool that enhances server navigation within SimpleCloud. With this plugin, users can click on designated signs to instantly connect to different servers within your network.

## Features

- [x] **Server Navigation**: Intuitive navigation within SimpleCloud using clickable signs. Instantly connect to other servers with ease.
- **Supported Server Software**: Supports Paper & Forks. Planned support for Spigot & Forks.
- **Quick Setup**: Easy installation process for all supported software.
- **Highly Configurable**: Customize behavior for various server states like `STARTING`, `ONLINE`, etc. se priorities and frame updates for animations.  
- **Placeholders**: Display real-time information with dynamic placeholders like `%group%`, `%player-count%`, and `%state%`.  
- **Dynamic Displays**:  Animated text frames for engaging and visually appealing signs.  
<details>
<summary>Screenshots</summary>

### Ingame Preview
![Preview](docs/plugin/signs/ingame_preview.png)

</details>

## Dependency

> For always up-to-date artifacts visit [dev artifects][dev-artifects] or [artifects][artifects].

> Note: If you want to use the dev version, you have to use the [snapshot repository][snapshots].

### Gradle Kotlin
```kt
implementation("io.github.solid-resourcepack:solid-api:VERSION")
```
### Gradle Groovy
```groovy
implementation 'io.github.solid-resourcepack:solid-api:VERSION'
```

### Maven
```xml
<dependency>
    <groupId>io.github.solid-resourcepack</groupId>
    <artifactId>solid-api</artifactId>
    <version>VERSION</version>
</dependency>
```

## Contributing
Contributions to SimpleCloud are welcome and highly appreciated. However, before you jump right into it, we would like you to read our [Contribution Guide][docs-contribute].

## License
This repository is licensed under [Apache 2.0][license].


<!-- LINK GROUP -->

<!-- ✅ PLEASE EDIT -->
[banner]: readme/banner/plugin/signs.png
[issue-bug-report]: https://github.com/theSimpleCloud/mylink/issues/new?labels=bug&projects=template=01_BUG-REPORT.yml&title=%5BBUG%5D+%3Ctitle%3E
[issue-feature-request]: https://github.com/theSimpleCloud/mylink/discussions/new?category=ideas
[docs-thisproject]: https://docs.simplecloud.app/contribute
[docs-contribute]: https://docs.simplecloud.app/contribute

[modrinth]: https://modrinth.com/organization/simplecloud
[maven-central]: https://central.sonatype.com/artifact/app.simplecloud.controller/controller-api
[dev]: https://repo.simplecloud.app/#/snapshots/app/simplecloud/controller/controller-api


[artifects]: https://repo.simplecloud.app/#/snapshots/app/simplecloud/controller/controller-api
[dev-artifects]: https://repo.simplecloud.app/#/snapshots/app/simplecloud/controller/controller-api

[badge-maven-central]: https://img.shields.io/maven-central/v/app.simplecloud.controller/controller-api?labelColor=18181b&style=flat-square&color=65a30d&label=Release
[badge-dev]: https://repo.simplecloud.app/api/badge/latest/snapshots/app/simplecloud/controller/controller-api?name=Dev&style=flat-square&color=0ea5e9

<!-- ⛔ DON'T TOUCH -->
[license]: https://opensource.org/licenses/Apache-2.0
[snapshots]: https://repo.simplecloud.app/#/snapshots

[social-x]: https://x.com/simplecloud.app
[social-bluesky]: https://x.com/simplecloud.app
[social-youtube]: https://www.youtube.com/@thesimplecloud9075
[social-discord]: https://discord.simplecloud.app

[badge-modrinth]: https://img.shields.io/badge/modrinth-18181b.svg?style=flat-square&logo=modrinth
[badge-license]: https://img.shields.io/badge/apache%202.0-blue.svg?style=flat-square&label=license&labelColor=18181b&style=flat-square&color=e11d48
[badge-discord]: https://img.shields.io/badge/Community_Discord-d95652.svg?style=flat-square&logo=discord&color=27272a
[badge-x]: https://img.shields.io/badge/Follow_@simplecloudapp-d95652.svg?style=flat-square&logo=x&color=27272a
[badge-youtube]: https://img.shields.io/badge/youtube-d95652.svg?style=flat-square&logo=youtube&color=27272a