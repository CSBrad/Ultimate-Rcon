<h1 align="center">
  <br>
    Ultimate Rcon
  <br>
</h1>

<h4 align="center">A Rcon Tool designed to simplify server commands!</h4>

<p align="center">
  <a href="https://github.com/CSBrad/Ultimate-Rcon/releases" target="_blank">
    <img alt="GitHub release (with filter)" src="https://img.shields.io/github/v/release/CSBrad/Ultimate-Rcon">
  </a>
  
  <a href="https://github.com/CSBrad/Ultimate-Rcon/releases" target="_blank">
    <img alt="GitHub all releases" src="https://img.shields.io/github/downloads/CSBrad/Ultimate-Rcon/total">
  </a>

  <a href="https://www.paypal.com/paypalme/BradleyRye" target="_blank">
    <img alt="Donate Today" src="https://img.shields.io/badge/Donate-Today-blue">
  </a>
  
  <a href="https://github.com/CSBrad/Ultimate-Rcon/releases/tag/v0.1.1.1" target="_blank">
    <img alt="Nightly Release" src="https://img.shields.io/badge/Nightly-Release-blue">
  </a>
  
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#platforms">Platforms</a> •
  <a href="#how-to-use">How to Use</a> •
  <a href="#launch-arguments">Launch Arguments</a> •
  <a href="#credits">Credits</a>
</p>

## Key Features
* **Built-in RCON**
  - Basic Rcon Functionality
  - Player List (coming soon)
  - Rcon Scheduler (coming soon)

## Installation

Ultimate-Rcon requires .NET 8.0. If you do not have .NET 8.0 installed, you can download it [here](https://dotnet.microsoft.com/en-us/download/dotnet/8.0) directly from Microsoft.

Download the latest available version from [here](https://github.com/CSBrad/Ultimate-Rcon/releases).

## Platforms
Currently tested on the following platforms:

* Microsoft Windows
  - 10
  - 11

## How to Use

For detailed guides on how to use Ultimate Rcon, please refer to the following resources:

* [Watch the Video](https://www.youtube.com/watch?v=CHfZ9D54PYE&t=3s)
* [Join the Discord](https://discord.com/invite/7GQYecCgtu)
* [Visit the Website](https://bradsdigitaltools.co.uk/)

## Launch Arguments

To launch with the developer console open, create a batch file with the following content:

```batch
@echo off
tasklist | find /i "UltimateRcon.exe" > nul
if errorlevel 1 (
    start "" "UltimateRcon" /console
) else (
    echo Application is already running.
)
```

## Credits
This software uses the following packages:
*  [RconSharp](https://github.com/stefanodriussi/rconsharp)
*  [Newtonsoft.Json](https://www.newtonsoft.com/json)

## Honourable Mentions 
A Massive thank you for supporting the project:
* Radiolotek
* Donatello

## Donations
This is free to use software. If you'd like to support future developments you can do so [Here](https://www.paypal.com/paypalme/BradleyRye) or [Here](https://github.com/sponsors/CSBrad/)
