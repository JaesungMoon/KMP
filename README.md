# KMP
Kotlin Multiplatform

[Compose Multiplatform](https://github.com/JaesungMoon/CMP)

install KMP plugin

```shell
% brew install kdoctor

% kdoctor
```

```shell
KMP % kdoctor                                                      (git)-[main]
Environment diagnose (to see all details, use -v option):
[✓] Operation System
[✓] Java
[!] Android Studio
  ! Android Studio (AI-242.23339.11.2421.12700392)
    Location: /Applications/Android Studio.app
    Bundled Java: openjdk 21.0.3 2024-04-16
    Kotlin Plugin: 242.23339.11.2421.12700392-AS
    Kotlin Multiplatform Mobile Plugin: not installed
    Install Kotlin Multiplatform Mobile plugin - https://plugins.jetbrains.com/plugin/14936-kotlin-multiplatform-mobile
[✖] Xcode
  ✖ Current command line tools: /Library/Developer/CommandLineTools
    You have to select command line tools bundled to Xcode
    Command line tools can be configured in Xcode -> Settings -> Locations -> Locations
[!] CocoaPods
  ! CocoaPods configuration is not required, but highly recommended for full-fledged development
  ✖ System ruby is currently used
    CocoaPods is not compatible with system ruby installation on Apple M1 computers.
    Please install ruby via Homebrew, rvm, rbenv or other tool and make it default
    Detailed information: https://stackoverflow.com/questions/64901180/how-to-run-cocoapods-on-apple-silicon-m1/66556339#66556339
  ✖ cocoapods not found
    Get cocoapods from https://guides.cocoapods.org/using/getting-started.html#installation

Conclusion:
  ✖ KDoctor has diagnosed one or more problems while checking your environment.
    Please check the output for problem description and possible solutions.
```

```shell
brew install cocoapods

xcode-select --install

sudo xcode-select -s /Applications/Xcode.app/Contents/Developer

[!] CocoaPods
  ! CocoaPods configuration is not required, but highly recommended for full-fledged development
  ✖ System ruby is currently used
    CocoaPods is not compatible with system ruby installation on Apple M1 computers.
    Please install ruby via Homebrew, rvm, rbenv or other tool and make it default
    Detailed information: https://stackoverflow.com/questions/64901180/how-to-run-cocoapods-on-apple-silicon-m1/66556339#66556339


brew install rbenv
brew install ruby
brew reinstall ruby
echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zprofile\nsource ~/.zprofile\n

```
