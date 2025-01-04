# Learn-DevOps

### The Learning Main Repo : https://github.com/hkhcoder/vprofile-project

## Required Tools : 
1. ORACLE VM VIRTUALBOX
2. GIT BASH
3. VAGRANT
4. CHOCOLATEY/BREW
5. JDK8
6. MAVEN
7. INTELLIJ
8. SUBLIME TEXT EDITOR
9. AWS CLI

## WindowsTools

Install chocolatey from the instructions given in the link below.

https://chocolatey.org/docs/installation

```
choco install virtualbox --version=7.1.4 -y
```
```
choco install vagrant --version=2.4.3 -y
```
```
choco install git -y
```
```
choco install corretto17jdk -y
```
```
choco install maven -y
```
```
choco install awscli -y
```
```
choco install intellijidea-community -y
```
```
choco install vscode -y
```
```
choco install sublimetext3 -y
```

## MacOS Tools

Install brew from the instructions given in the link below.


https://brew.sh/

After installing homebrew
Create a file in users home directory with name .curlrc with content “-k” 
(-k without quotes and give a new line character after -k.)

Steps:

1. OpenTerminal
2. Execute below command
```
echo -k > ~/.curlrc
```
3. Execute below command to see -k in file ~/.curlrc 
```
cat ~/.curlrc
```

Run all the below commands in Terminal


### (virtualbox command is not For MacOs M1/M2)
```
brew install --cask virtualbox 
```
```
brew install --cask vagrant
```
```
brew install --cask vagrant-manager
```
```
brew install git
```
```
brew install openjdk@17
```
```
sudo ln -sfn $HOMEBREW_PREFIX/opt/openjdk@17/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk.jdk
```
```
exec zsh -l
```
```
brew install maven
```
```
brew install --cask visual-studio-code
```
```
brew install --cask intellij-idea
```
```
brew install --cask intellij-idea-ce
```
```
brew install --cask sublime-text
```
```
brew install awscli
```



## AWS : 
1. FREE TIER ACCOUNT
2. IAM WITH MFA
3. BILLING ALARM
4. CERTIFICATE SETUP 
