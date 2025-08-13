<img width="1000" height="560" alt="477581690-5ca0d27d-48ee-4753-9775-791eea3823c8" src="https://github.com/user-attachments/assets/a63fd5a2-a8d6-456d-b047-5690a81ba7f4" />

## Ceremony Rehber ; 

#### Gerekenler ; 

GitHub hesabınız aşağıdaki kriterleri karşılamalıdır: 
- En az bir aylık. 
- En az bir genel repo. 
- En az 5 GitHub hesabı takip ve en az 1 takipçisi olmalıdır. 
- Ceremony araçlarının hesabınızdaki GitHub Gist'lerini okumasına ve yazmasına izin vermelidir.

## 1. Sunucu Güncelleme

```bash
sudo apt update -y && sudo apt upgrade -y
```

## 2. Gerekli Paketleri Yükleme

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file unzip lz4 -y
```

## 3. NVM ; 

```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
source .bashrc
```

```bash
nvm install 18 
nvm use 18
```

```bash
source ~/.bashrc
```

## Ceremony Adımları

- Dosya Oluşturma ; 

```bash
mkdir ~/trusted-setup-tmp && cd ~/trusted-setup-tmp
```

- CLI İndirme 

```bash
npm install -g @p0tion/phase2cli
```

```bash

```
