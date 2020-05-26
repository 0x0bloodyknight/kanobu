# 🗿✂️📄 Kanobu
## 🗣 Localisation
| Language      | Status    | Language    | Status   |
|---------------|-----------|-------------|----------|
| 🇷🇺 Russian    | 👍 stable | 🇩🇪 German     | ⚠️ beta  |
| 🇺🇦 Ukrainian  | 👍 stable | 🇬🇧 English    | 👍 stable |
| 🇫🇷 French     | 🗓 plans  | 🇪🇸 Spanish    | 🗓 plans |
| 🇨🇳 Chinese    | ❌ none   | 🇵🇹 Portuguese | 🗓 plans |
| 🇵🇱 Polish     | 🗓 plans   | 🇮🇹 Italien    | 🗓 plans  |
| 🇹🇷 Turkish    | ❌ none   | 🇸🇦 Arabien    | ❌ none  |
| 🇰🇷 Korean     | ❌ none   | 🇮🇳 Hindi      | ❌ none  |
| 🇭🇺 Hungarian  | 🗓 plans  | 😀 Emoji     | ⚠️ beta  |

## 🧑‍💻 Installation
To install, you must download repository and dependencies:
```
git clone https://github.com/jDan735/kanobu.git
cd kanobu
pip install -r requirements.txt
```
## 🚀 Start
To start, run this code:
```
python ropasci.py
```
Also you can use option, example `python ropasci.py --dev`
### ⚙️ Options
#### dev
For get developers functions (`log`, `clog`), and logs about variables and other parameters
#### **[PLANS]** mode
For change game mode, for create you must write you mode in `config.cson`
#### **[PLANS]** lang
For set default language. All languages place in `locale`
#### **[PLANS]** test
For test
#### **[PLANS]** help
For get help
## ⚒ Build
Build supported on all popular os (`Windows`, `Mac OS`, `Linux`). You can build for your platform, not other
```
pip install cx_Freeze
python setup.py build
```
Then copy `locale` to `build/<app>`
## 🔨 Dependencies
### 🖌 [colorama](https://github.com/tartley/colorama)
Simple cross-platform colored terminal text in Python. Support `cmd`, `bash`
### 📄 [pycjson](https://github.com/avakar/pycson)
A Coffescript Object Notation (CSON) parser. Help write configs for humans. Based on `CoffeeScript`
## 📰 Trello (ru)
You can subscribe to [trello](https://trello.com/b/o0ozs1XT) to get information about the new functionality
