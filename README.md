<div align="center">
<img src="https://raw.githubusercontent.com/jishinmonitor/meta/main/App-Github-Banner.png" alt="Jishin Monitor">
</div>

[Read Japanese version (日本語版を読む)](https://github.com/jishinmonitor/meta/blob/main/README_JP.md)

# [COMING SOON] Jishin Alert (地震監視)
**Earthquake and Tsunami Warnings for Android - 地震・津波警報 Android版**
A Japan earthquake monitoring app for Android that delivers EEWs, earthquake information, tsunami warnings and pulls information from official government sources such as JMA and NIED.

## Features
* Real time seismic intensity and PGA information map from NIED observation points
* Earthquake Early Warnings and Tsunami Warnings
* Multi-event display support
* Detailed earthquake reports

## Feature Roadmap
| Feature | Beginning Date | Completion Date |
|---------|--------------|----------------|
| Observation points database Romaji translation | January 17, 2022 | TBD |
| Backend app server | TBD | TBD |
| NTP synchronization | TBD | TBD |
| Earthquake Information Report | TBD | TBD |
| Strong-motion monitor map | TBD | TBD |
| EEW notifications | TBD | TBD |
| Tsunami warning display | TBD | TBD |

## Licensing and Liability
* JishinAlert is closed-source proprietary software. You may not decompile, reverse engineer or reuse any assets, resources, images, sounds included without permission.
* This app is meant as a helpful tool. **There are no warranties associated with this app. We are not responsible for any issues that arise from using this app.** For example: if the app doesn't work and before you know it, furniture crush you, or a tsunami hits your house, or if you run away because there is a false alert issued, we won't be responsible. **Official sources, such as JMA website, NHK, Area Mail, etc. always take precedence over this app.** When in doubt, **please check those.**
* JishinAlert receives Earthquake Forecasts, Earthquake Early Warning bulletins from the Japan Meteorological Agency (JMA). The user must [understand how it works and how to respond to it](https://www.jma.go.jp/jma/en/Activities/eew.html) before downloading and using the app.

## Downloads
This project is not yet completed.

## Programming Languages
Kotlin & Go

## Credits
* Map data: Google Maps
* EEW, real-time intensity and PGA data: National Research Institute for Earth Science and Disaster Prevention (NIED)
* P2PQuake for tsunami information

Special thanks to:
* JQuake for image analysis algorithm [(Article: 多項式補間を使用して強震モニタ画像から数値データを決定する)](https://qiita.com/NoneType1/items/a4d2cf932e20b56ca444) and [tsunami areas GeoJSON](https://gist.github.com/wolf20482/864da7dd76b31efe55c6a7e025a6e015)
* [ingen084](https://github.com/ingen084) for [observation points database](https://github.com/jishinalert/observation-points)
