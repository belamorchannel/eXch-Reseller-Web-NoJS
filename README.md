
```
git clone https://github.com/belamorchannel/eXch-Reseller-Web-NoJS.git
```
```
cd eXch-Reseller-Web-NoJS
```

```
sudo apt update
```
```
sudo apt install python3-pip python3-venv tor
```
```
python3 -m venv venv
```
```
source venv/bin/activate
```
```
pip install -r requirements.txt
```

```
sudo systemctl start tor
```
```
sudo systemctl enable tor
```
