<img alt="TimeLapze" src="https://github.com/wkaisertexas/ScreenTimeLapse/assets/27795014/d79916bd-e0d5-4da1-85ce-4bf95f0f44fb" />

<h1 align="center">TimeLapze</h1>

<p align="center">
  A menu bar application for creating screen and camera timelapses while keeping file sizes manageable
</p>

<p align="center">
  <a href="#introduction"><strong>Introduction</strong></a> ·
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#installation"><strong>Installation</strong></a> ·
  <a href="#local-development"><strong>Local Development</strong></a> ·
  <a href="#tech-stack"><strong>Tech Stack</strong></a> ·
  <a href="#contributing"><strong>Contributing</strong></a>
</p>
<br/>

## Introduction

<p align="center">
  <img width="553" alt="Application demonstration photo in menu bar" src="https://github.com/wkaisertexas/ScreenTimeLapse/assets/27795014/785ee2b6-1ef5-4302-83da-c3d81a069074">
</p>

<p align="center">
  <i>TimeLapze</i> is a minimalist, menu bar application for creating color accurate screen and camera timelapses while keeping file sizes manageable
</p>

<p align="center">
<img alt="color accurate comparision" src="https://github.com/wkaisertexas/ScreenTimeLapse/assets/27795014/ca37fa51-7851-4080-9e8c-f95f9ed529a8"></img>
Color accuracy is an important feature which prevents you from recording washed-out, photocopied-looking time lapses
</p>


## Features

- **Color-Accurate**: What you see is what you get. Never screen record faded videos again[^1]
- **Minimalist Design**: a fully featured menu bar recorder
- **Hardware Accelerated**: fully utilized hardware accelerated encoding for a lightweight recording experience
- **Space Saving**: Avoid the excessive file sizes of high quality video (can be as high as 7 GB / hour)
- **Camera Recording**: Record your webcam or phone with the same frame rate and camera speed
- **Secure**: Use the fully features of `ScreenCaptureKit` to only record certain windows, applications and more. Never leak your bank information in recordings again!
- **Customizability**: Change everything from the frame rate, quality and speed multiple

## Installation

### App Store (Recommended)

Get **Timelapse** on the App Store:  
[Download on the App Store](https://apps.apple.com/us/app/timelapze/id6473860445)

### Homebrew  

Install **TimeLapze** via [Homebrew](https://brew.sh/):

```bash
brew install timelapze
```

### Direct Download  

Download the latest version from the [Releases page](https://github.com/wkaisertexas/ScreenTimeLapse/releases).  

1. Download `TimeLapze.zip`
2. If Chrome or Safari warns about the file, ignore it
3. Extract the archive to get `TimeLapze.app`
4. Move it to your `Applications` folder

## Local Development

To develop TimeLapze locally, you will need to clone and open this repository in XCode.

Once that's done, you can use the following commands to run the app locally:

```console
git clone https://github.com/wkaisertexas/ScreenTimeLapse
cd ScreenTimeLapse
open TimeLapze.xcodeproj
```

Following this, you need to allow the app to be built for local signing. 

## Tech Stack

- [SwiftUI](https://developer.apple.com/documentation/swiftui/)
- [ScreenCaptureKit](https://developer.apple.com/documentation/screencapturekit/)
- [AVFoundation](https://developer.apple.com/av-foundation/)
- [CoreMedia](https://developer.apple.com/documentation/coremedia)

## Contributing

Contributions are welcome! Here's how you can contribute:

- [Open an issue](https://github.com/wkaisertexas/ScreenTimeLapse/issues) if you believe you've encountered a bug
- Submit a [pull request](https://github.com/wkaisertexas/ScreenTimeLapse/pull) to add features, improve usability, or fix bugs

<a href="https://github.com/wkaisertexas/ScreenTimeLapse/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=wkaisertexas/ScreenTimeLapse" />
</a>

## Repo Activity

![Screen Time Lapse Repo Activity](https://repobeats.axiom.co/api/embed/3c10f8fa2ca2324639b9986cb38043750550c993.svg "Repobeats analytics image")

## License

TimeLapze is released under the [MIT License](LICENSE), ensuring open-source availability

> [!IMPORTANT]
> If you liked this project, consider giving the repository a star ⭐️!

[^1]: [Apple's screen recorder converts the display's color space](https://community.adobe.com/t5/premiere-pro-discussions/inaccurate-colors-from-desktop-recording/m-p/12168181) from **DCI_P3** to **sRGB**. This subtle error makes it unsuitable for color-sensitive work. Even [HDR video struggles with persistent overexposure issues in screenshots](https://github.com/iina/iina/issues/3866). 
