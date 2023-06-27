# CheckMK Schlung

How to start:

- clone the git repo locally and `cd` into it
- run the following commands (copy/paste to terminal will work):
```BASH
if [[ $(uname) == "Linux" ]]; then
    sudo apt install python3.8-venv
fi
python3 -m venv venv
. venv/bin/activate
pip3 install --upgrade pip
pip3 install -r requirements.txt
```
- open the repo in VS code (if you are on Linux, open it inside WSL using `code .`)
- Install `Python` and the `Jupyter` extensions
- configure VS code's Python interpreter to use your venv:
    * View -> Command Palette
    * Type `Python: Select Interpreter`
    * Choose `./venv/bin/python`
- configure VS code's Jupyter Server to use your venv:
    * View -> Command Palette
    * Type `Jupyter: Select Interpreter to Start Jupyter Server`
    * Choose `venv`

You're ready to go. Have fun!
