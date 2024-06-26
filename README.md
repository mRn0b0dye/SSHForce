# SSHForce

## About
Python SSH brute-forcer for educational testing of login security.
## Installation
To install ```sshforce```, follow these steps:
```
git clone https://github.com/mRn0b0dye/SSHForce
cd SSHForce
pip install -r requirements.txt
chmod +x sshforce.py
```
## Usage
### Help
```
python sshforce.py -h
```

<img width="713" alt="image" src="https://github.com/mRn0b0dye/SSHForce/assets/114957011/1211c3d8-d286-4951-91f6-0aac6e230440">

## Examples
- Using wordlist
```
python sshforce.py -i 192.168.1.12 -u root -P list
```
- Using both wordlist and usernames list
```
python sshforce.py -i 192.168.1.12 -U list -P list1
```
- Using usernames list only
```
python sshforce.py -i 192.168.1.12 -U list -p linux
```
