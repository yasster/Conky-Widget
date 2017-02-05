# Conky-Widget

A theme for [conky](https://github.com/brndmtthws/conky) powered by [OpenWeatherMap](http://openweathermap.org/).

It displays useful information to the user from the PC/Computer and Weather.

---

* [Compatibility](#compatibility)
* [Installation](#installation)
* [API-key](#api-key)
* [City](#city)
* [Language](#language)
* [Units](#units)

---

####Compatibility:

The latest version of this theme is on the master branch, and it supports conky `1.10.x`.

For older versions, check the available [releases](../../releases).

---

###Installation

* Install **conky**, **curl** and **jq**.

* Install the [Poiret One](https://www.google.com/fonts/specimen/Poiret+One) font.

* Move the `.conky-vision-icons` folder & `.conkyrc` file into your `~` dir.

**NOTE** some files/folders are hidden; unhide them. :smile:

---

###API Key

For now, you need to register a private API key on [OpenWeatherMap](http://openweathermap.org/) to get weather data.

Place the API key in the `template6` variable inside the `.conkyrc`file.

---

###City

[Find the ID of your city](http://openweathermap.org/help/city_list.txt) and place it inside the `template7` variable inside the `.conkyrc` file.

---

###Language

By default this conky will use your default locale.

Edit the `template9` variable in the `.conkyrc` file to change the language.

---

###Units

Edit the `template8` variable inside the `.conkyrc` file to change the units.

---

###Colors

* Edit the `color` variables inside the `.conkyrc` file to change **text** color.

* To change the **icon** colors, first use the `render-pngs` script to render a folder of icons with the desired color, then change the icon sources in the `.conkyrc` file under the `Icon Sources` section.
    * The script uses the `SVG` folder to render png's.

    * You should keep the size at **32(px)** for this conky.


---

<img src="preview.png" id="preview">

*I've Hidden MAC and IP address for security reason. One last note, if you use a different WLAN or LAN card make sure to change it in the '.conkyrc' file.
