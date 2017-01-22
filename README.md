# Neo2 Keyboard Layout for AnySoftKeyboard
Provides Neo2 keyboard layouts for the AnySoftKeyboard App on Android.

## Installation
* First install AnySoftKeyboard, which is available from [F-Droid](https://f-droid.org/repository/browse/?fdfilter=anysoft&fdid=com.menny.android.anysoftkeyboard).
* Then install the Neo2 keyboard layout, which is also available from [F-Droid](https://f-droid.org/repository/browse/?fdfilter=neo&fdid=com.anysoftkeyboard.languagepack.neo).

## Features
* Arrow keys
* CTRL key
* Tab Key
* Special characters as pop-ups
* Physical keyboard (work in progress)

## Known Issues
* If Shift not working as expected update to latest ask (F-droid not up to date and will bug)
* No Mod 3 and 4
* The only thing changed in physical keyboard are the letters

## Building from source
You need to have an appropriate Android SDK, its platform tools and gradle installed.
To create an APK you need to [create a keystore](http://stackoverflow.com/questions/3997748/how-can-i-create-a-keystore).

Execute the following commands with your keystore and key information.

```bash
export PACK_KEYSTORE_PASSWORD="yourpassword"
export PACK_KEYSTORE_ALIAS="keyalias"
export PACK_KEYSTORE_KEY_PASSWORD="keypswd"
gradle build
```

If there was no error you can find the APK in the directory `build/outputs/apk`.

## License

* All code unless specified:
    Copyright 2013 Menny Even-Danan
    
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
    http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
* Keyboard layout XMLs or specified in file head:
    Copyright 2016, kertase

    This file is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License    
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
* Dictionary files:
 igerman98 - dictionaries for German language
 Copyright (C) 1999-2016 Björn Jacke <bjoern@j3e.de>.

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License version 2 or 3 as
    published by the Free Software Foundation.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program; if not, write to the Free Software
    Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
and for wiktrny_de files:
     Dictionnary derived from the titles of [[de.wiktionary.org]] articles by the Wiktionary contributors liscensed under CC BY-SA 3.0 https://creativecommons.org/licenses/by-sa/3.0/
