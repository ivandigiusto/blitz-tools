# blitz-tools
Python scripts to analyze WoT Blitz replays and stats:

### Replays
* [wotbreplay_uploader.py](wotbreplay_uploader.py): An asynchronous replay uploader. Requires [Python 3.7](https://www.python.org/downloads/) or higher.
* [postwotreplay.py](postwotreplay.py): A simple WoT Replay uploader. Prints the received JSON from https://wotinspector.com

### Tank data
* [getTankopedia.py](getTankopedia.py): Get the lastest tankopedia data from wotinspector.com. The script fetches only a limited set of data. You may edit to your needs. 
* [extractTankopedia.py](extractTankopedia.py): Extract Blitz data directly from the Blitz app files. You need to download the Blitz App APK package and unzip it to a folder. Requires [Python 3.7](https://www.python.org/downloads/) or higher.

### Utils
* [WG_utils.py](WG_utils.py): A utils class for various Wargaming API related to functions. Other scripts use this, so you need to place it to the same folder with the other scripts

### Data
* [tanks.json](tanks.json): Tankopedia in WG JSON format extracted from the Blitz app files with [extractTankopedia.py]](extractTankopedia.py]). Contains only limited information required by the scripts. Blitz version 5.3. 
* [maps.json](maps.json): Blitz map names extracted from the Blitz app files with [extractTankopedia.py]](extractTankopedia.py]). Blitz version 5.3.
