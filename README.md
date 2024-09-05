# Mobile testingsssss
#SETUP
1. Run the command `xcodebuild -downloadPlatform iOS` in your computer terminal to download and install iOS Simulator runtimes
2. Run a test, for example `maestro test onboarding-ios.yaml
   ` and follow the steps to select the device to run on
3. Incase you have a maestro start up exception, try and increase the timeout by running `export MAESTRO_DRIVER_STARTUP_TIMEOUT=60000`
