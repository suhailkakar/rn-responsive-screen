
<div align="center">
<img src="https://img.shields.io/badge/Contributors-1-success?style=for-the-badge" >
<img src="https://img.shields.io/badge/issues-0%20open-yellow?style=for-the-badge" >
<img src="https://img.shields.io/badge/LICENSE-MIT-green?style=for-the-badge" >
<img src="https://camo.githubusercontent.com/1ffde4ea8d2869a62cdf80282516c524e1109befc83d6339aae7a55d94ff4ae5/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d4c696e6b6564496e2d626c61636b2e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d6c696e6b6564696e26636f6c6f72423d353535" >
</div>



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="#">
    <img src="https://i.ibb.co/5jxbdxW/2235672.png" alt="Logo" width="100" height="100">
  </a>

  <h3 align="center">RN Responsive Screen</h3>

  <p align="center">
    Small Package used for responsiveness in your react native app !
    <br />
    <a href="https://www.npmjs.com/package/rn-responsive-screen"><strong>NPM Package »</strong></a>
    <br />
    <br />
     </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

<img src="https://i.pinimg.com/originals/2a/f0/0b/2af00b77b9831ccf199a7360d8d4d39f.gif">

Responsive app design is an approach to app design that makes its screen render well on a variety of devices and window or screen sizes


**Responsive design** can help you solve a lot of problems for your **app**. It will make your app user -friendly, improve the way it looks on devices with both large and small screens, and increase the amount of time that visitors spend on your app.

### Built With

* [React Native](https://reactnative.dev)



<!-- GETTING STARTED -->
## Getting Started

### Installation

* npm
  ```sh
  npm install --save rn-responsive-screen
  ```
* yarn
  ```sh
  yarn add rn-responsive-screen
  ```




<!-- USAGE EXAMPLES -->
## Usage


```javascript
import { StatusBar } from "expo-status-bar";
import React from "react";
import { StyleSheet, Text, View } from "react-native";
import { widthToDp, heightToDp } from "rn-responsive-screen";

export default function App() {
  return (
    <View style={styles.container}>
      <Text style={styles.test}>
        Open up App.js to start working on your app!
      </Text>
      <StatusBar style="auto" />
    </View>
  );
}
const styles = StyleSheet.create({
  test: {
    marginTop: heightToDp("10%"),
    width: widthToDp("30%"),
  },
});

  ```




<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch
3. Commit your Changes 
4. Push to the Branch
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Name - [@suhailkakar](https://twitter.com/suhailkakar)

Email - [suhail.zahed@gmail.com](mailto:suhail.zahed@gmail.com)

Website - [suhailkakar.com](https://suhailkakar.com) 

Project Link: [https://www.npmjs.com/package/rn-responsive-screen](https://www.npmjs.com/package/rn-responsive-screen)


