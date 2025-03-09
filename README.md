# GLP_healthcare_app
## This is a repository for GLP Phase2 Project

# healthcare_app

A React Native application built with [Expo](https://expo.dev/) to help users cook their meal at home.

## Table of Contents
1. [Prerequisites](#prerequisites)
2. [Clone the Repository](#clone-the-repository)
3. [Set Up a Python Virtual Environment (Optional)](#set-up-a-python-virtual-environment-optional)
4. [Install Node Dependencies](#install-node-dependencies)
5. [Additional Required Packages](#additional-required-packages)
6. [Running the App](#running-the-app)
7. [Using the Expo Client App](#using-the-expo-client-app)
<!-- 8. [Troubleshooting](#troubleshooting)
9. [License](#license) -->

---

## Prerequisites

1. **Node.js**
   - Make sure you have a recent version of Node installed. Recommended: Node 16 or newer.
   - You can check by running:
     ```bash
     node -v
     ```

2. **npm**
   - Comes bundled with Node. You can check by running:
     ```bash
     npm -v
     ```

3. **Expo CLI** (Global Install)
   - Install or update globally if you plan on using Expo from the command line:
     ```bash
     npm install --global expo-cli
     ```
   - Check your Expo version:
     ```bash
     expo --version
     ```

4. **Git**
   - Installed for cloning this repository.

> **Note**: A Python environment is not strictly required for an Expo project, but if you have Python-related scripts or testing processes, you can optionally set it up. See the [Set Up a Python Virtual Environment](#set-up-a-python-virtual-environment-optional) section below.

---

## Clone the Repository

```bash
git clone https://github.com/mimo-owl/GLP_healthcare_app.git
cd GLP_healthcare_app
```

## Set Up a Python Virtual Environment (Optional)
If you have Python scripts or dependencies in this repo (for example, for backend services or data processing), you may want to create a Python virtual environment. Otherwise, you can skip this step.

1. **Create a virtual environment in the current directory**
   - Make sure you are under the directory `/healthcare_app` when running:
     ```bash
     python3 -m venv .healthcare_app_env
     ```

2. **Activate the virtual environment**
   - You can activate by running:
     ```bash
     source .healthcare_app_env/bin/activate
     ```

## Install Node Dependencies

Inside the healthcare_app project folder, install the necessary dependencies from package.json:
```bash
npm install
```

## Additional Required Packages

This app relies on several Expo and React Native community packages that are not part of a default Expo installation. To ensure your environment includes these, install each one as follows:

```bash
# Notifications
npx expo install expo-notifications

# Battery status
npx expo install expo-battery

# Async storage
npx expo install @react-native-async-storage/async-storage

# Modal date/time picker (and native date-time picker dependency)
npx expo install react-native-modal-datetime-picker @react-native-community/datetimepicker

# Slider
npx expo install @react-native-community/slider

# React Navigation
npx expo install @react-navigation/native
npx expo install @react-navigation/stack
```

## Running the App

Once dependencies are installed, you can move to `/healthcare-app` by running:
```bash
cd healthcare-app
```

Then, start the Expo development server:
```bash
npx expo start
```

## Using the Expo Client App
1.	Install the Expo Go App on your iOS or Android device.
2.	Scan the QR code shown in your terminal or browser window.
3.	The app should load on your device via the Expo Go client.
