# GTOI
Graph Theory for Olympiad in Informatics

# How to make the book?
one time:
```
download npm and node at https://nodejs.org/en/
git clone https://github.com/shaazzz/GTOI.git
sudo apt-get install python3-sphinx
sudo npm install -g http-server
```

after every change:
```
cd GTOI
./scripts/build.sh
cd _build
http-server
```
