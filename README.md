
pkg upgrade -y

pkg install python -y

pkg install git


git clone https://github.com/Marketplaceid/yoAdderTele

cd yoAdderTele

python setup.py

python scraper.py

python adder.py
