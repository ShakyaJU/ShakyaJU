<p align="center">
  <img src="https://raw.githubusercontent.com/ShakyaJU/ShakyaJU/main/hello-world-terminal.gif" alt="Hello World Terminal" width="700"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ShakyaJU&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/ShakyaJU/ShakyaJU/main/my-intro.svg" alt="Intro" width="700"/>
</p>

<p align="center">
  <a href="#flagship"><img src="https://img.shields.io/badge/Featured%20Project-Pok%C3%A9Pod-FBC02D?style=for-the-badge&logo=flutter&logoColor=white" alt="Featured project: PokéPod" valign="middle"></a>
  <a href="#projects"><img src="https://img.shields.io/badge/More%20Projects-02569B?style=for-the-badge" alt="More Projects" valign="middle"></a>
  <a href="#stack"><img src="https://img.shields.io/badge/Tech%20Stack-43A047?style=for-the-badge" alt="Tech Stack" valign="middle"></a>
  <a href="#connect"><img src="https://img.shields.io/badge/Get%20in%20Touch-E53935?style=for-the-badge" alt="Get in Touch" valign="middle"></a>
</p>

---

<a id="flagship"></a>

## 🚀 Featured Project

<div align="center">

<a href="https://github.com/ShakyaJU/pokepod">
  <img src="https://raw.githubusercontent.com/ShakyaJU/ShakyaJU/main/pokepod_splash_text.png" alt="PokéPod" width="300">
</a>

<h3>Beyond the Pokédex.</h3>

<p>An unofficial Pokémon research, challenge and discovery companion, built end to end with Flutter.</p>

<p>
  <img src="https://img.shields.io/badge/Flutter-3.47.4-02569B?logo=flutter&logoColor=white" alt="Flutter 3.47.4">
  <img src="https://img.shields.io/badge/Dart-3.10-0175C2?logo=dart&logoColor=white" alt="Dart 3.10">
  <img src="https://img.shields.io/badge/State-Riverpod-0891B2" alt="Riverpod">
  <img src="https://img.shields.io/badge/Platform-Android-3DDC84?logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/Data-Pok%C3%A9API-EF5350" alt="PokéAPI">
  <img src="https://img.shields.io/badge/Storage-Local--first-5EEAF2" alt="Local-first storage">
  <img src="https://img.shields.io/badge/License-MIT-E91E63" alt="MIT License">
</p>

<p><b>1,025 species · 9 generations · 20 achievements · 4 widget sizes · 327 tests</b></p>

<p>
  <a href="https://github.com/ShakyaJU/pokepod"><img src="https://img.shields.io/badge/View%20the%20Repository-24292F?style=for-the-badge&logo=github&logoColor=white" alt="View the PokéPod repository"></a>
  <a href="https://drive.google.com/file/d/1mC15HkOd97j_yW7tOFx_2wqBNsXa5Kaf/view?usp=sharing"><img src="https://img.shields.io/badge/%E2%96%B6%20%20Watch%20the%20Full%20Demo-02569B?style=for-the-badge" alt="Watch the full PokéPod demo"></a>
</p>

</div>
<!--
<p align="center">
  <img src="https://raw.githubusercontent.com/ShakyaJU/ShakyaJU/main/pokepod-overview.png" alt="PokéPod — complete application overview" width="100%">
</p>
-->
PokéPod treats the Pokédex as a research instrument rather than a list. You browse the Pokédex, record what you have discovered, studied and mastered, compare specimens, build teams and play a daily "Who's That Pokémon?" challenge. Everything is stored "locally on the device" no account, no backend.

<table align="center">
  <tr>
    <td align="center" valign="top" width="33%">
      <img src="https://raw.githubusercontent.com/ShakyaJU/ShakyaJU/main/whos that pokemon challenge.gif" alt="Who's That Pokémon? daily challenge being played" width="220"><br>
      <sub><b>Who's That Pokémon?</b><br>Daily challenge with a progressive reveal</sub>
    </td>
     <td align="center" valign="top" width="33%">
      <img src="https://raw.githubusercontent.com/ShakyaJU/ShakyaJU/main/pokedex.gif" alt="Pokédex · searched, filtered and sorted" width="220"><br>
      <sub><b>Pokédex</b><br>Pokédex · search, filters and sorting</sub>
    </td>
    <td align="center" valign="top" width="33%">
      <img src="https://raw.githubusercontent.com/ShakyaJU/ShakyaJU/main/evolution constellation.gif" alt="Evolution Constellation graph being explored" width="220"><br>
      <sub><b>Evolution Constellation</b><br>Interactive evolution graph</sub>
    </td>
    <td align="center" valign="top" width="33%">
      <img src="https://raw.githubusercontent.com/ShakyaJU/ShakyaJU/main/app widgets.gif" alt="PokéPod home-screen widgets in four sizes" width="220"><br>
      <sub><b>Android widgets</b><br>Demo for two widgets</sub>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="50%" valign="top">

**🔭 Research, not just a list**
Discovered, Studied and Mastered stages that only you advance.

**🧬 Analysis that explains itself**
Two-Pokémon comparison, data-backed "Unexpected Connections" and team coverage with written reasoning.

**🎯 A daily challenge**
One Pokémon per local calendar day, six guesses, progressive clues, streaks and a staged picture reveal.

</td>
    <td width="50%" valign="top">

**📱 Native Android widgets**
The Specimen of the Day on the home screen in four sizes.

**🔔 Opt-in local reminders**
Scheduled in the device's time zone, with permission explained before the system prompt.

**🏆 20 achievements, 9 rarity tiers**
Unlocked from real progress, each with a progress bar.

</td>
  </tr>
</table>

### What it demonstrates

- **State and dependency injection with Riverpod.** One mechanism for state, repositories and the HTTP client; tests override any of them.
- **A cache-first repository layer.** Screens never see HTTP; identical in-flight requests are de-duplicated, and previously opened content works offline.
- **Domain logic in pure Dart.** The type chart, team analysis, filtering, sorting, evolution layout, achievements and the daily challenge are tested without any UI (327 automated tests).
- **Careful game design.** A date-seeded shuffle of the full National Dex, a saved answer per day, explicit win and loss states, and fair streak rules.
- **Local-first privacy.** No accounts, analytics or ads; backup and restore with validation and confirmation.
- **Honest documentation.** The README lists known limitations, such as Android-only widgets and the platforms that have not been built.

<p align="center">
  <img src="https://img.shields.io/badge/Dio-networking-5C6BC0" alt="Dio">
  <img src="https://img.shields.io/badge/shared__preferences-persistence-455A64" alt="shared_preferences">
  <img src="https://img.shields.io/badge/home__widget-widgets-3DDC84?logo=android&logoColor=white" alt="home_widget">
  <img src="https://img.shields.io/badge/flutter__local__notifications-reminders-F57C00" alt="flutter_local_notifications">
  <img src="https://img.shields.io/badge/audioplayers-sound-8E24AA" alt="audioplayers">
</p>

<p align="center"><sub>PokéPod is an unofficial fan project and is not affiliated with Nintendo, The Pokémon Company or Game Freak. Pokémon names and artwork belong to their respective owners.</sub></p>

<p align="center"><a href="https://github.com/ShakyaJU/pokepod"><b>Explore PokéPod on GitHub →</b></a></p>

---

<a id="projects"></a>

## 🌟 More Projects

### 📈 [Bull & Bear](https://github.com/ShakyaJU/bull-and-bear)

<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/NEPSE-market%20data-455A64" alt="NEPSE market data">
  <img src="https://img.shields.io/badge/Storage-local-5EEAF2" alt="Local storage">
</p>

<table>
  <tr>
    <td width="60%" valign="top">
      <h4>📱 Features</h4>
      <ul>
        <li><strong>Home Dashboard</strong> — NEPSE index, market summary, top gainers and losers.</li>
        <li><strong>Watchlist</strong> — track favorite stocks and price changes.</li>
        <li><strong>Market</strong> — search listed companies by name, symbol, or sector.</li>
        <li><strong>Portfolio</strong> — track holdings, investment value, and profit/loss.</li>
        <li><strong>Settings &amp; Data</strong> — theme customization, manual refresh, auto-refresh, and app information.</li>
        <li><strong>Data Fallback</strong> — labels demo data when the live feed is unavailable.</li>
        <li><strong>Custom Branding</strong> — branded splash screen and app icon.</li>
        <li><strong>Navigation</strong> — Home, Watchlist, Market, Portfolio, and More.</li>
      </ul>
      <h4>⚠️ Disclaimer</h4>
      <p><sub>Bull &amp; Bear uses an unofficial NEPSE data API for educational purposes and is not affiliated with NEPSE. Prices may be delayed; demo data is clearly labeled. Portfolio data is stored locally and is not connected to any broker or bank.</sub></p>
    </td>
    <td width="40%" align="center" valign="top">
      <a href="https://github.com/ShakyaJU/bull-and-bear">
        <img src="https://github.com/ShakyaJU/ShakyaJU/blob/main/bull%26bear.gif" alt="Bull & Bear App Preview" width="280">
      </a>
    </td>
  </tr>
</table>

---

### 🍽️ [Food Allergen Detection](https://github.com/ShakyaJU/Food_Allergen_Detection)

<p>
  <img src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Keras-CNN-D00000?logo=keras&logoColor=white" alt="Keras CNN">
</p>

<table>
  <tr>
    <td width="60%" valign="top">
      <h4>📱 Key Features</h4>
      <ul>
        <li><strong>Image Upload</strong> — upload food images for allergen detection.</li>
        <li><strong>Real-Time Camera</strong> — capture food images directly through the mobile app.</li>
        <li><strong>Machine Learning</strong> — uses a CNN model to analyze food images and predict potential allergens.</li>
        <li><strong>Flutter Interface</strong> — a mobile-friendly interface for submitting images and viewing predictions.</li>
      </ul>
      <h4>🚀 Technologies Used</h4>
      <ul>
        <li><strong>Frontend:</strong> Flutter (Dart)</li>
        <li><strong>Backend:</strong> Flask (Python)</li>
        <li><strong>Machine Learning:</strong> TensorFlow/Keras, CNN, ResNet50V2</li>
      </ul>
      <h4>⚠️ Disclaimer</h4>
      <p><sub>Predictions are model-generated and may not identify every allergen. Do not rely on this application alone to determine whether food is safe for someone with an allergy.</sub></p>
    </td>
    <td width="40%" align="center" valign="top">
      <a href="https://github.com/ShakyaJU/Food_Allergen_Detection">
        <img src="https://github.com/ShakyaJU/ShakyaJU/blob/main/f_a_d.gif" alt="Food Allergen Detection App Preview" width="280">
      </a>
    </td>
  </tr>
</table>

---

<a id="stack"></a>

## 🛠 Tech Stack

<table align="center">
  <tr>
    <td align="center"><b>Mobile</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=flutter,dart,firebase" alt="Flutter, Dart, Firebase" /></td>
  </tr>
  <tr>
    <td align="center"><b>AI &amp; Backend</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=python,flask,tensorflow" alt="Python, Flask, TensorFlow" /></td>
  </tr>
  <tr>
    <td align="center"><b>Languages</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=typescript,java" alt="TypeScript, Java" /></td>
  </tr>
  <tr>
    <td align="center"><b>Tools</b></td>
    <td align="center"><img src="https://skillicons.dev/icons?i=vscode,git,vercel" alt="VS Code, Git, Vercel" /></td>
  </tr>
</table>

---

<a id="connect"></a>

## 📬 Connect with Me

<p align="center">
  <a href="https://linkedin.com/in/justin-shakya-b56174239" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://kaggle.com/justinshakya" target="_blank">
    <img src="https://img.shields.io/badge/Kaggle-black?style=for-the-badge&logo=kaggle&logoColor=white" alt="Kaggle" />
  </a>
  <a href="mailto:jushakya34@gmail.com">
    <img src="https://img.shields.io/badge/Email-red?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

<p align="center"><sub>Open to Flutter and mobile development conversations. Thanks for stopping by.</sub></p>
