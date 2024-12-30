# NOTE

This was a fork of the original `react-native-reusables` template starter base for testing an issue (https://github.com/drizzle-team/drizzle-studio-expo/issues/7) I was encountering with `drizzle-studio-expo`. 

 - React-Native-Reusables (RNR) - https://rnr-docs.vercel.app/getting-started/initial-setup/
 - Drizzle Studio for Expo SQLite - https://github.com/drizzle-team/drizzle-studio-expo

 Fortunately, creating this minimal reproduction highlighted the issue and I was able to fix my app. The issue was that I needed to update to the latest expo@52 and switch to the `newArchEnabled=true` in `app.json`.

# Starter base

A starting point to help you set up your project quickly and use the common components provided by `react-native-reusables`. The idea is to make it easier for you to get started.

## Features

- NativeWind v4
- Dark and light mode
    - Android Navigation Bar matches mode
    - Persistant mode
- Common components
    - ThemeToggle, Avatar, Button, Card, Progress, Text, Tooltip

<img src="https://github.com/mrzachnugent/react-native-reusables/assets/63797719/42c94108-38a7-498b-9c70-18640420f1bc"
     alt="starter-base-template"
     style="width:270px;" />