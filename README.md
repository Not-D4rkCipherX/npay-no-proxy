# NODEPAY FARMING WTHOUT PROXIES
- Multi Account Keep-Alive Support.

# NOTE
- **Paste your nodepay tokens inside ```tokens.txt```**
- 
# PC (WINDOWS)
## How to Get Nodepay Token -

1. Open your browser and login to the NODEPAY dashboard.
2. Press `F12` to open the **Inspect Elements** panel.
3. Go to the **Console** tab and paste the following code:
```
localStorage.getItem('np_webapp_token') 
```

4. You will receive your user ID, which looks like this: `"eyJhbG........"`
5. If you can't paste, type `allow pasting` and press Enter.

## Recommended Python Version

It is recommended to use **Python 3.10**.  
[Download Python 3.10 here](https://www.python.org/downloads/release/python-3100/).

## Install Requirements

Run the following command to install the necessary packages:

```
pip install -r requirements.txt
```

## Running the Script

```
python bot.py
```
# FOR ANDROID

## How to Get NODEPAY User ID Using Android Device

1. Download and install [Kiwi Browser](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser&hl=en).
2. Login to the NODEPAY web and go to the dashboard.
3. Open the **Developer Tools** in the Kiwi browser.
4. Go to the **Console** tab and paste this code:
```
localStorage.getItem('np_webapp_token') 
```

5. If you can't paste, type `allow pasting` and press Enter, then paste the line above.

## Open TERMUX APP & Clone This Script
```
pkg install git
```
```
git clone https://github.com/Not-D4rkCipherX/npay-no-prxy.git
```
## Install Requirements
```
pip install -r requirements.txt
```
## Put your token(s) inside ```token.txt```
```
pkg install nano
```
```
nano tokens.txt
```
```
python bot.py
```
