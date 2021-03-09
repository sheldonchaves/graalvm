# graalvm macosX

### Install GRAALVM
```
  brew install --cask  graalvm/tap/graalvm-ce-java11
```
### xattr
```
  sudo xattr -r -d com.apple.quarantine /Library/Java/JavaVirtualMachines/graalvm-ce-java11-21.0.0
```
### install native image
```
  /Library/Java/JavaVirtualMachines/graalvm-ce-java11-21.0.0/Contents/Home/bin/gu install native-image
```
### export GRAALVM_HOME
```
  export GRAALVM_HOME=/Library/Java/JavaVirtualMachines/graalvm-ce-java11-20.3.0/Contents/Home
```
