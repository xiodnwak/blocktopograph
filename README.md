# Blocktopograph

- This fork is trying to support MCBE 1.20+ for Android 10+ (*Storage Access Framework*)
- Improve UI and more valid NBT editing ways

> Working on level.dat editor ui

## Technical Support

* Android SDK Version

|    Minium     |          Target          |
|:-------------:|:------------------------:|
| Oreo - 8 (26) | UpsideDownCake - 14 (34) |

* Storage Privacy

| Min Android Version |       Method       |
|:-------------------:|:------------------:|
|       8 (26)        | Directly with File |
|      11+ (30)       |      Shizuku       |

* Minecraft World Version

| Version | Support Status |
|:-------:|:--------------:|
|  1.20+  |  *Processing*  |

## Demo (Android 13)

![Storage Request Permission](./assets/Screenshot_20240310_174304.png)
![Main](./assets/Screenshot_20240310_174321.png)

## Build

Clone project in Android Studio: `File -> New -> Project from Version Control -> Git`
Install missing SDK components. Android Studio would give you the auto-fix options.

Or Manual

```shell
git clone https://github.com/NguyenDuck/blocktopograph.git
cd blocktopograph
./gradlew build assembly
```

## Contributing

Always welcome! Fork the project, improve and publish!
