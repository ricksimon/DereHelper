# DereHelper

本项目为偶像大师灰姑娘手游的安卓端非官方工具APP</br>

Helper Android APP for THE iDOLM@STER Cinderella Girls: Starlight Stage(デレステ). All the data is from API provided by other sites and has nothing to do with the official application.

## API used
* **Card and Character(Chinese)** http://starlight.346lab.org
* **Card and Character(English)** https://starlight.kirara.ca
* **Image** https://truecolor.kirara.ca

## Building
* Require Android Studio 2.3 (Will move to 3.0 later...)
* Comment the signingConfigs & google services(analytics) in gradle files(\DereHelper\app\build.gradle), because the related files are private.

## Screenshot

![](https://github.com/Lazyeraser/DereHelper/raw/master/art/beat_map.jpg)

## Features
* Card
* Chara
* BeatMap

And more in development
## Language
Provides UI string resource file `strings.xml` for localization in `/app/src/main/res`
### Folders

    values - English // default
    values-ja - Japanese
    values-zh-* - Chinese // Traditional & Simplified

## License
    Copyright(C) 2017 Lazyeraser
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.