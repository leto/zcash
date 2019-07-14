 # **INSTALLATION PROCESS**

## **_Getting Started_**

### Recommended System Specs:

2 or more CPU threads
64-bit Linux(Ubuntu 16.04)
4+ GB RAM
20+ GB Storage

## **Building for Linux from source**

### Install Ubuntu/Debian dependencies

```
sudo apt-get update && sudo apt-get upgrade -y
sudo apt-get install build-essential pkg-config libc6-dev m4 g++-multilib autoconf libtool ncurses-dev unzip git python python-zmq zlib1g-dev wget curl bsdmainutils automake
```
### **Install Fedora dependencies (if not using Ubuntu/Debian OS)**
```
sudo dnf install git pkgconfig automake autoconf ncurses-devel python python-zmq wget gtest-devel gcc gcc-c++ libtool curl patch
```
### **Build arrowd**

```
1. git clone https://github.com/Arrowchain/arrow.git arrow
2. cd arrow
3. git checkout arrow-1927
4. ./zcutil/build.sh -j$(nproc)
```

### **Create config file**
```
1. mkdir ~/.arrow
2. echo "rpcuser=username" >> ~/.arrow/arrow.conf
3. echo "rpcpassword=`head -c 32 /dev/urandom | base64`" >> ~/.arrow/arrow.conf
4. echo "rpcallowip=127.0.0.1" >> ~/.arrow/arrow.conf
5. echo "addnode=110.185.105.21:7654" >> ~/.arrow/arrow.conf
6. echo "addnode=18.204.209.173:7654" >> ~/.arrow/arrow.conf
7. echo "addnode=110.185.105.21:7654" >> ~/.arrow/arrow.conf
8. echo "addnode=195.10.210.35:7654" >> ~/.arrow/arrow.conf
9. echo "addnode=80.11.223.136:7654" >> ~/.arrow/arrow.conf
10. echo "addnode=52.90.76.26:7654" >> ~/.arrow/arrow.conf
11. echo "addnode=52.90.76.26:7654" >> ~/.arrow/arrow.conf
```

### **Fetch params**

```
1. cd arrow
2. ./zcutil/fetch-params.sh
```

### **Run arrowd**

```
./src/arrowd
```

## **Building for MacOS from source**

### Install dependencies

```
1. #install xcode
2. xcode-select --install
3. 
4. /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
5. brew install cmake autoconf libtool automake coreutils pkgconfig gmp wget
6. 
7. brew install gcc5 --without-multilib

```
### **Build**

```
1. git clone https://github.com/Arrowchain/arrow.git arrow
2. cd arrow
3. git checkout arrow-1927
4. ./zcutil/build.sh -j$(sysctl -n hw.ncpu)

```
## **Fetch params**

``` 
./zcutil/fetch-params.sh
 ```

### **Create config file**
```
1. mkdir ~/Library/Application Support/arrow/
2. echo "rpcuser=username" >> ~/Library/Application Support/arrow/arrow.conf
3. echo "rpcpassword=`head -c 32 /dev/urandom | base64`" >> ~/Library/Application Support/arrow/arrow.conf
4. echo "rpcallowip=127.0.0.1" >> ~/Library/Application Support/arrow/arrow.conf
5. echo "addnode=110.185.105.21:7654" >> ~/Library/Application Support/arrow/arrow.conf
6. echo "addnode=18.204.209.173:7654" >> ~/Library/Application Support/arrow/arrow.conf
7. echo "addnode=110.185.105.21:7654" >> ~/Library/Application Support/arrow/arrow.conf
8. echo "addnode=195.10.210.35:7654" >> ~/Library/Application Support/arrow/arrow.conf
9. echo "addnode=80.11.223.136:7654" >> ~/Library/Application Support/arrow/arrow.conf
10. echo "addnode=52.90.76.26:7654" >> ~/Library/Application Support/arrow/arrow.conf
11. echo "addnode=52.90.76.26:7654" >> ~/Library/Application Support/arrow/arrow.conf
```
### **Run arrowd**

``` 
./src/arrowd
 ```

@ArrowTeam
