### Purpose
This script extracts all birthday-entries from abook and creates recurring appointments in calcurse.

#### abook:
Abook is a text-based addressbook program designed to use with mutt mail client.
(--> [https://abook.sourceforge.io/](https://abook.sourceforge.io/)

#### calcurse:
calcurse is a calendar and scheduling application for the command line.
(--> [https://www.calcurse.org/](https://www.calcurse.org/)

### Run the script
- edit `config.py`:
    - assign `DIR_ABOOK` to the folder where your abook files are stored. Its usually in a folder called `.abook`in your home directory.
    - assign `DIR_CALCURSE` to the folder where your calcurse files are stored. Its usually in a folder called `.calcurse` in your home directory.
    - make sure `config.py` is located in the same directory as `main.py`
- backup `.abook/addressbook` and `.calcurse/apts`
- open Terminal and cd in the directory of `main.py`
- run the script via the command `python main.py`
