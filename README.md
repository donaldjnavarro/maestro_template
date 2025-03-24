# Maestro Template

Maestro is an automation framework for native apps. This template provides a basic set of files to support a quick start for a project using this tool.

## Known Limitations

* Maestro does not support real iOS devices being connected to the computer. It only supports emulated devices (As of 2025-03-24)
* iOS emulation is not supported on Windows

## Setup

### Initial Setup

1. Install Maestro (See [Maestro Installation Guide](https://docs.maestro.dev/getting-started/installing-maestro))
2. Install emulators (Such as Android Studio)

### Session Setup

1. Either launch an emulated device, or virtualize a real device (Usually within Android Studio)
2. Install the APK you want to test on the test device (In Android Studio, drag and drop an APK file directly into the virtual device display)

## Usage

Example command:
`maestro test <testfile>` for example `maestro test android-advanced-flow.yaml`
