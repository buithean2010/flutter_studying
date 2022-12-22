# Flutter setup notes

- Flollow by the official [Flutter setup guide](https://docs.flutter.dev/get-started/install), I write this note to memorize what I had done to setup the evironment.
- You are required to install Xcode, Command Line Tools for Xcode (for iPhone app build) and Android studio (for Android app build) before installing Flutter.

## Step 1
- Download the latest version of Flutter which suits for your PC/Mac from Flutter [official site](https://docs.flutter.dev/get-started/install)
- Extract the downloaded zip file to ~/Dev/Tools/flutter
(You can change the path as what ever you want to)

## Step 2
Follow [these steps](https://docs.flutter.dev/get-started/install/macos#update-your-path) to update the flutter path.
- Open VS Code.
- Select **Terminal > New Terminal** from the menu to open the integrated terminal.
- Add the following line to the **$HOME/.zshrc** file

    > export PATH="$PATH:$HOME/Dev/Tools/flutter/bin"

- Run **source $HOME/.zshrc** to refresh the terminal window.
- Verify that the flutter command is available
    > which flutter

## Step 3
Run **flutter doctor** to check  if there are any dependencies you need to install to complete the setup and follow the result guide.

