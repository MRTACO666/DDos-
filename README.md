Termux

pkg update -y && pkg upgrade -y
pkg install python -y
pip install time
pip install colorama
pip install threading
pip install socket
pip install requests
git clone https://github.com/pixxxionix/satoshi
cd satoshi
python satoshi.py
