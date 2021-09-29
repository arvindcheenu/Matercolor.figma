[![Matercolor Figma Plugin](https://github.com/arvindcheenu/figma-matercolor/blob/master/src/app/assets/Matercolor-plugin-header.png?raw=true)](#readme)
## 🎨 Matercolor
**🧩 A Figma Plugin** that generates Material Color Palettes for any Color based on the latest Material Color System Guidelines.

<a href="https://www.figma.com/community/plugin/872008431843787391"><img src="https://github.com/arvindcheenu/figma-matercolor/blob/master/src/app/assets/install-on-figma-button.png?raw=true" height="50px"></a>

### 🚸 &nbsp;Usage

> **✨ New in v.2.0.0 : More palette varieties!** 
>
> Updated to work with the latest version of Matercolor. 
> **Resolves [issue #2](https://github.com/isarvindone/figma-matercolor/issues/2)**: Enables 3-letter and 6-letter hex code input (with or without hash prefix) while also supporting selection via. color picker. 
> **Resolves [issue #3](https://github.com/isarvindone/figma-matercolor/issues/3)**: More freedom in naming and grouping palettes. Simply use `/` to nest palettes. 

<p align="center">
  <br/><b>👟 &nbsp;Run the Plugin &nbsp;🧩</b></br>
<a href="#-usage"><img src="https://github.com/arvindcheenu/figma-matercolor/blob/master/src/app/assets/usage-screenshots/Usage-1.png?raw=true" height="200px"/></a>
 <br/>↓</br>
   <br/><b> 🖌️&nbsp;Use it!</b></br></br>
<a href="#-usage"><img src="https://github.com/arvindcheenu/figma-matercolor/blob/master/src/app/assets/usage-screenshots/Usage-2.png?raw=true"width="90%"/></a>
</p>

### 👐 &nbsp;Contributor's Checklist
- [x] Before planning to contribute, create a ✨ **new Issue** ✨ so that we can discuss and improve on your proposed changes.
- [x] Fork and clone this repository using `git clone https://github.com/arvindcheenu/Matercolor.figma.git`
- [x] Go to this directory using `cd figma-matercolor`
- [x] Run `yarn` to install dependencies.
- [x] Run `yarn build:watch` to start webpack in watch mode.
- [x] Open <kbd>Figma</kbd> → <kbd>Plugins</kbd> → <kbd>Development</kbd> → <kbd>New Plugin...</kbd> and choose `manifest.json` file from this repo.
- [x] To change the UI of your plugin (the react code), start editing [App.tsx](./src/app/components/App.tsx).  
- [x] To interact with the Figma API edit [controller.ts](./src/plugin/controller.ts).  
- [x] For plugin development-related information, checkout [Figma API Overview](https://www.figma.com/plugin-docs/api/api-overview/).
- [x] As you make changes, create a **Draft Pull Request** referencing your issue using `#[issue-number]` and Happy Commiting!
- [x] Happy with how your code works? Finalise your changes and open up your Pull Request for **Review**.
- [x] After a few tantalizing review sessions, ✨ **have a cup of ☕ and watch as your code gets merged!** ✨

### &nbsp;🧰 Toolings
<table>
<tr>
  <td align="center"><a href="#-toolings"><img src="https://cdn4.iconfinder.com/data/icons/logos-3/600/React.js_logo-512.png" width="50px"/></a></td>
  <td align="center"><a href="#-toolings"><img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Typescript_logo_2020.svg" width="50px"/></a></td>
  <td align="center"><a href="#-toolings"><img src="https://github.com/webpack/media/blob/master/logo/icon.png" width="50px"/></a></td>
  <td align="center"><a href="#-toolings"><img src="https://upload-icon.s3.us-east-2.amazonaws.com/uploads/icons/png/11490474241551942136-512.png" width="50px"/></a></td>
</tr>
<tr>
  <td align="center"><a href="https://github.com/facebook/react"><b>React</b></a></td>
  <td align="center"><a href="https://github.com/microsoft/TypeScript"><b>TypeScript</b></a></td>
  <td align="center"><a href="https://github.com/webpack/webpack"><b>Webpack</b></a></td>
  <td align="center"><a href="https://github.com/prettier/prettier"><b>Prettier</b></a></td>
</tr>
</table>

### &nbsp;🌀 Versioning
Follows [**Keep a Changelog**](https://keepachangelog.com/en/1.0.0/) and [**Semantic Versioning**](https://semver.org/spec/v2.0.0.html) specifications. To know more about the changes made across the versions, see the [**tags on this repository**](https://github.com/arvindcheenu/Matercolor.figma/tags). 

### 📜 &nbsp;License

This project is licensed under the [**GPL-3.0 License**](LICENSE.md).
