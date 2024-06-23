<p align="center">
  <img width="460" height="300" alt="logo of keyfinder" src="https://raw.githubusercontent.com/geeknik/keyFinder/master/css/icon.png">
</p>
<hr></hr>

<p align="center">
<img src="https://img.shields.io/badge/Firefox-126+-orange"/>
<img src="https://img.shields.io/github/license/momenbasel/keyFinder"/>
<img src="https://img.shields.io/github/downloads/geeknik/keyFinder/total.svg"/>
</p>


# What is keyFinder?
keyFinder is Firefox extension that searches the DOM for any embedded script link, as script tag may contain keys for specific API(such as Google maps API) and you can add keywords to search for it at any website you visit.


## Features:
* it searches the DOM for "src" of scripts and see if it contains certain words such as "keys" and save them.
* it works at background
* it is expandable(as you can add words to it)


## Installation

1. git clone https://github.com/geeknik/KeyFinder.git
2. open Firefox and and go to `about:debugging#/runtime/this-firefox`
3. Click `Load Temporary Add-on`
4. browse to the `manifest.json` in the keyFinder folder


## Disclaimer
This tool is for educational purposes only. You are responsible for your own actions. If you break any laws while using this Firefox extension, it's your fault.

Contact:
[@geeknik](https://twitter.com/geeknik)

Author of the original Chrome extension: [@momenbassel](https://twitter.com/@momenbassel)
