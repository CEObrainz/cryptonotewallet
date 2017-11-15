# Instructions

Note: To perform the instructions below make sure you run these commands (based on Ubuntu 14.04).

```sudo apt-get install build-essential git cmake libboost1.55-all-dev```

**1. Clone wallet sources**

```
git clone https://github.com/CEObrainz/otakoin-wallet.git
```

**2. Set symbolic link to coin sources at the same level as `src`.**
```
git submodule add https://github.com/CEObrainz/cryptonote-otakoin.git cryptonote
```
**4. Build**

```
mkdir build && cd build && cmake .. && make
```
