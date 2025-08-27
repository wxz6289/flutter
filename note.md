```zsh
export PUB_HOSTED_URL="https://pub.flutter-io.cn"
export FLUTTER_STORAGE_BASE_URL="https://storage.flutter-io.cn"
unzip flutter_macos_arm64_3.35.2-stable.zip
sudo chown -R $USER /opt/flutter
flutter doctor
sudo softwareupdate --install-rosetta --agree-to-license
```

- XCode 调试和编译原生 Swift 或 ObjectiveC 原生代码
- cocoaPods 在原生应用中编译并启用 Flutter 插件
- Flutter extension for VS Code

安装并配置XCode

```zsh
sudo sh -c 'xcode-select -s /Applications/Xcode.app/Contents/Developer && xcodebuild -runFirstLaunch'
sudo xcodebuild -license
xcodebuild -downloadPlatform iOS
open -a Simulator

sudo gem install
export PATH=$HOME/.gem/bin:$PATH
```
