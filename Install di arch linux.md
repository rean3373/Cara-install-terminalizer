# Install di Arch linux

## Update sistem

``` 
pacman -Syu
```

## Install node.js versi 22.22.3

```
# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.4/install.sh | bash

# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"

# Download and install Node.js:
nvm install 22

# Verify the Node.js version:
node -v # Should print "v22.22.3".
```

## Install Terminalizer

```
npm install -g terminalizer
```

## Cek versi terminalizer

```
terminalizer --version
```

# Tampilannya

<img width="667" height="444" alt="image" src="https://github.com/user-attachments/assets/bbb42c1b-13b5-466b-bb39-bd29066ba20b" />

## Penggunaan terminalizer

### 1. Cek versi
Masukan prompt

```
terminalizer --version
```

Kalo muncul hasilnya, lanjut step 2

### 2. Memulai Record Terminalizer

bikin nama folder record 

contoh:

```
terminalizer record tester
```
**Nama tester ganti sesuai kebutuhan**

**nanti akan mucul tab cmd baru nah pas munculnya tab baru itu sedang merekam prompt kalian**


### 3. Mengakhiri Record Terminalizer dan render hasilnya

**Stop rekam : klik ctrl+d**

lalu

```
terminalizer render tester
```


** Contoh hasil dari terminalizer**

![render1767084290348](https://github.com/user-attachments/assets/3296e8c5-b8d8-47b1-b4c0-92ad69e7ddd8)
