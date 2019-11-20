# acrcloud_music_scan
 a bash script that produces csv file with a list of track names and artists when run in a folder of wav files.

requirements:
python
acrcloud_sdk_python and acrcloud_scan_files_python

python-Levenshtein
fuzzywuzzy
backports.csv
requests
openpyxl
python-dateutil

you need an acrcloud api key.
edit acrcustom.py to include your key.

get acrcloud_scan_files_python on the acrcloud github:

https://github.com/acrcloud/acrcloud_scan_files_python

install acrcloud sdk:
python -m pip install git+https://github.com/acrcloud/acrcloud_sdk_python
