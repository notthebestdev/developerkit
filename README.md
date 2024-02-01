<p align="center">
 <img src="Icon.png" alt="DeveloperKit"></a>
</p>

<h3 align="center">⚙️ DeveloperKit</h3>

DeveloperKit is an shortcut that brings many tools into one shortcut without having to spend long times copying shortcuts.

## 🚀 Summary

- [About the project](#-about-the-project)
 - [Functions](#-functions)
- [Documentation](#-documentation)
  - [Options](#%EF%B8%8F-options)
- [Download](#-download)

## 📖 About the project

**DeveloperKit** on iOS is like having a magic wand for your tools – no more copying and pasting shortcuts! It's your handy sidekick, making your developer life smoother. 🪄

Picture this: a friend that gathers all your favorite tools in one place. With **DeveloperKit**, you glide through tasks effortlessly, no need for tricky shortcuts. It's like having a backstage pass to an iOS concert where everything just flows – easy, breezy, and all about you getting things done. Enjoy the magic of **DeveloperKit**, turning your iOS adventure into a breeze! 🚀✨

## 🪄 Functions

| Feature            | Description                                                       | Options                    |
|--------------------|-------------------------------------------------------------------|----------------------------|
| Version            | Retrieves the version of the DeveloperKit.                        |                            |
| Ping               | Pings a specific IP and returns the response time in milliseconds.| ip                         |
| ConnectedToWifi?   | Indicates whether the user is currently connected to Wi-Fi.       |                            |
| ConnectedToInternet?| Indicates whether the user is currently connected to the internet.|                            |
| Location           | Quickly and simply retrieves the user’s current location.         |                            |
| RunJavaScript      | Executes a provided JavaScript code.                              | code                       |
| Timezone           | Retrieves the timezone of the user.                               |                            |
| CensorText         | Censors the provided text.                                        | text                       |
| UserLanguage       | Retrieves the preferred language of the user.                     |                            |
| CheckForUpdates    | Checks for updates via RoutineHub.                                | id, version                |
| BatteryLeft        | Displays the remaining battery percentage.                        |                            |
| Boolean            | Returns a boolean response.                                       | response                   |
| GetUserName        | Retrieves the username of the user.                               |                            |

## 📕 Documentation

To use DeveloperKit: it's easy to understand!

First, you need to have a dictionary, it's the main entry for DeveloperKit.
<img src="/Screenshots/1.png" alt="" width="500" height="auto">

You will always use this for DeveloperKit, no more things are required after this.

Then, in the screenshot, we need to put a specific request.
> [!WARNING]
While doing this step, make sure to put a correct request or else things may break!

For this tutorial, we are gonna use the **UserLanguage** feature. 
This allows us to retrieve the user's language so that we can translate the shortcut's text into the user's language.

<img src="https://github.com/notthebestdev/developerkit/assets/129324066/e3946664-619f-4bbd-9f8c-a4d8e89dccfb" alt="" width="500" height="auto">

If you do everything correctly, you should see a result with the user's language (example: fr-FR)

# 🎛️ Options

You can add options to requests because they are needed.

Let's do for example the function: **RunJavascript**.

*RunJavascript is a feature that executes a provided JavaScript code via the option "code".*

<img src="https://github.com/notthebestdev/developerkit/assets/129324066/d34750e6-83f8-400c-b97c-e031d1ccac08" alt="" width="500" height="auto">

This code:
```
<html>
  <head>
    <script>
    	var random = Math.floor(Math.random() * 100) + 1;
      document.write(random);
    </script>
  </head>
  <body></body>
</html>
```
generates a **random number** from 0 to 100.

Example Result: 42.

## 📲 Download

You can [click here](https://routinehub.co/shortcut/17888/) to download.
Or [click here](https://www.icloud.com/shortcuts/e1db2c2adbef4f99b1dab8e1b591726d) if the link below doesn't work.

<a class="copyrighted-badge" title="Copyrighted.com Registered &amp; Protected" target="_blank" href="https://app.copyrighted.com/work/6F7WlGgDjwNPkhbT"><img alt="Copyrighted.com Registered &amp; Protected" border="0" width="125" height="25" srcset="https://static.copyrighted.com/badges/125x25/04_2_2x.png 2x" src="https://static.copyrighted.com/badges/125x25/04_2.png"></a>
