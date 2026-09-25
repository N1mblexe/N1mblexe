<!--
  Profile README for github.com/N1mblexe
  - assets/banner.svg   : hand-built banner (Unity Animator graph, text outlined, animated with CSS)
  - profile/*.svg       : stats cards, regenerated daily by .github/workflows/readme-cards.yml
  Lines marked TODO are placeholders only you can fill in. HTML comments never render on GitHub.
-->

<p align="center">
  <img src="./assets/banner.svg" width="100%" alt="Ahmet Çevik, gameplay programmer at 2E. The banner is drawn as a Unity Animator graph that cycles through Idle, Run, Jump and Fall states." />
</p>

<p align="center">
  <a href="https://store.steampowered.com/developer/2E"><img alt="2E on Steam" src="https://img.shields.io/badge/Steam-2E-262626?style=for-the-badge&logo=steam&logoColor=white&labelColor=1b1b1b" /></a>
  <a href="https://play.google.com/store/apps/details?id=com.mvs.roboroar"><img alt="Roboroar on Google Play" src="https://img.shields.io/badge/Google_Play-Roboroar-262626?style=for-the-badge&logo=googleplay&logoColor=white&labelColor=1b1b1b" /></a>
  <a href="https://apps.apple.com/app/id6473368433"><img alt="Roboroar on the App Store" src="https://img.shields.io/badge/App_Store-Roboroar-262626?style=for-the-badge&logo=appstore&logoColor=white&labelColor=1b1b1b" /></a>
  <a href="https://www.linkedin.com/in/ahmet-%C3%A7evik-c7/"><img alt="Ahmet Çevik on LinkedIn" src="https://img.shields.io/badge/LinkedIn-Ahmet_%C3%87evik-262626?style=for-the-badge&labelColor=1b1b1b" /></a>
  <a href="mailto:ahmetcevik774@gmail.com"><img alt="Email Ahmet" src="https://img.shields.io/badge/Email-Get_in_touch-262626?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1b1b1b" /></a>
</p>

## About

I'm the core gameplay programmer at **[2E](https://store.steampowered.com/developer/2E)**, an independent two-person studio with four released games on Steam and a fifth in development. I build the parts players feel before they can name them: core mechanics, gameplay loops, state machines, and event-driven systems that keep features from tangling into each other.

I started in 2019 writing C for Arduino and ESP32 boards, then moved into games.

- Designed the in-game economy and battle pass for **Roboroar**, a multiplayer mech arena on Android and iOS with 10K+ downloads on Google Play
- 🥈 2nd place at the Konya Technical University Project Fair with a VR simulation built in Unity and Blender
- Currently building **[HeHe Remake](https://store.steampowered.com/app/3152740/HeHe_Remake/)** at 2E <!-- TODO: confirm, or replace with what you're actually on -->

## Games

<table>
  <tr>
    <td colspan="2" align="center">
      <a href="https://store.steampowered.com/app/3152740/HeHe_Remake/"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/3152740/header.jpg" width="460" alt="HeHe Remake Steam header art" /></a><br />
      <b>HeHe Remake</b>, in development<br />
      <sub>Mining survival underground, hunted by ReRe's spawn. <a href="https://store.steampowered.com/app/3152740/HeHe_Remake/">Wishlist on Steam</a></sub>
      <!-- TODO: one line on the system you own here, e.g. "I built the enemy spawner and the dig/terrain system." -->
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://store.steampowered.com/app/2269530/HaHa/"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/2269530/header.jpg" width="100%" alt="HaHa Steam header art" /></a><br />
      <b>HaHa</b>, 2024<br />
      <sub>Arena shooter roguelite against endless enemy hordes</sub>
      <!-- TODO: your contribution -->
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://store.steampowered.com/app/3193830/HiHi/"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/3193830/header.jpg" width="100%" alt="HiHi Steam header art" /></a><br />
      <b>HiHi</b>, 2024<br />
      <sub>Vertical platformer: jump up, don't fall</sub>
      <!-- TODO: your contribution -->
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top">
      <a href="https://store.steampowered.com/app/2183790/BadDraw/"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/2183790/header.jpg" width="100%" alt="Bad-Draw Steam header art" /></a><br />
      <b>Bad-Draw</b>, 2024<br />
      <sub>2D platformer about a hand-drawn character's revenge</sub>
      <!-- TODO: your contribution -->
    </td>
    <td width="50%" align="center" valign="top">
      <a href="https://store.steampowered.com/app/1946650/hehe/"><img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1946650/header.jpg" width="100%" alt="hehe Steam header art" /></a><br />
      <b>hehe</b>, 2022<br />
      <sub>2D platform survival: a sugar cube versus the tea monster</sub>
      <!-- TODO: your contribution -->
    </td>
  </tr>
</table>

## What I build

| System | What it solves | Where it shipped |
| --- | --- | --- |
| **State machines** | Character, AI and game-flow states without if/else sprawl | 2E games |
| **Event systems** | Decoupled messaging, so gameplay systems never hold hard references to each other | 2E games |
| **Economy and battle pass** | Reward pacing and progression balance for a live free-to-play game | [Roboroar](https://play.google.com/store/apps/details?id=com.mvs.roboroar) (MVS Games) |
| **Developer console** | Source-engine-style runtime console for testing and debugging in builds | [Unity-Console-Asset](https://github.com/N1mblexe/Unity-Console-Asset) |
| **VR simulation** | Full VR project modelled in Blender, built in Unity | KTUN Project Fair, 2nd place |

<!-- TODO: every row without a code link is a claim a reviewer can't check. Extract one system per month into a small public repo with a GIF and link it here. -->

## Tools

<p>
  <img alt="Unity" src="https://img.shields.io/badge/Unity-262626?style=for-the-badge&logo=unity&logoColor=white" />
  <img alt="C#" src="https://img.shields.io/badge/C%23-262626?style=for-the-badge&logo=dotnet&logoColor=8E6CF0" />
  <img alt="C++" src="https://img.shields.io/badge/C%2B%2B-262626?style=for-the-badge&logo=cplusplus&logoColor=659AD2" />
  <img alt="C" src="https://img.shields.io/badge/C-262626?style=for-the-badge&logo=c&logoColor=A8B9CC" />
  <img alt="Blender" src="https://img.shields.io/badge/Blender-262626?style=for-the-badge&logo=blender&logoColor=E87D0D" />
  <img alt="Git" src="https://img.shields.io/badge/Git-262626?style=for-the-badge&logo=git&logoColor=F05032" />
</p>
<p>
  <sub>From the embedded days:</sub><br />
  <img alt="Arduino" src="https://img.shields.io/badge/Arduino-262626?style=flat-square&logo=arduino&logoColor=00979D" />
  <img alt="ESP32" src="https://img.shields.io/badge/ESP32-262626?style=flat-square&logo=espressif&logoColor=E7352C" />
  <img alt="Linux" src="https://img.shields.io/badge/Linux-262626?style=flat-square&logo=linux&logoColor=FCC624" />
</p>

## GitHub activity

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile/stats-dark.svg" />
    <img height="165" alt="GitHub stats for N1mblexe" src="./profile/stats-light.svg" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile/top-langs-dark.svg" />
    <img height="165" alt="Most used languages across N1mblexe's public repositories" src="./profile/top-langs-light.svg" />
  </picture>
</p>

<sub>Most of my production code lives in private studio repositories, so these cards only show part of the picture.</sub>

---

<p align="center">
  <sub>Ankara, Türkiye. Turkish (native) and English.<br />
  Want to see what I work on next? <a href="https://store.steampowered.com/app/3152740/HeHe_Remake/">Wishlist HeHe Remake</a>.</sub>
</p>
