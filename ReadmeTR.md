<img width="1000" height="560" alt="477581690-5ca0d27d-48ee-4753-9775-791eea3823c8" src="https://github.com/user-attachments/assets/a63fd5a2-a8d6-456d-b047-5690a81ba7f4" />

## Ceremony Rehber ; 

#### Gerekenler ; 

- Sunucu yada Windows WSL - Açık kalması önemli. Ben normal 4 CPU 8 Ram'li diğer nodelerin bulunduğu serverda başlattım.
- İnternet hızınız iyi olmadı birazda disk alanınız olsun.

#### GitHub hesabınız aşağıdaki kriterleri karşılamalıdır: 
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

- Github Auth ; 

```bash
phase2cli auth
```

- Başladıktan Sonra Size Kod Vericek Github Auth ile bağlanmamız lazım 15 Dakika içinde.
- Link : https://github.com/login/device

<img width="555" height="576" alt="image" src="https://github.com/user-attachments/assets/556635d4-d1c8-42ff-b1ad-48de878534c4" />


- Kod Komut sonrası ekranda çıkacak.

<img width="750" height="390" alt="image" src="https://github.com/user-attachments/assets/75c4d39c-fc12-45c0-8b36-fdf07a549fe2" />

- Bağladıktan sonra ; 

<img width="757" height="450" alt="image" src="https://github.com/user-attachments/assets/bb55d849-9ea3-473c-8b1c-14acc6f3a5cb" />

## Ceremony Katılım ; 

- Screen Açalım

```bash
screen -S ceremony
```

```bash
phase2cli contribute -c ethstorage-v1-trusted-setup-ceremony
```

<img width="754" height="389" alt="image" src="https://github.com/user-attachments/assets/56403d4e-35b6-45c7-a23c-c8af74d856d5" />


- Ben Random seçtim direkt entere bastım sorduğu kısımda sonra sıraya alıyor.

- Çıkmak için CTRL A+D Yapabilirsiniz

- screen -r ceremony komutu ile yeniden screene girip kontrol edebilirsiniz.


## Hatalar İçin ; 

<img width="902" height="128" alt="image" src="https://github.com/user-attachments/assets/b637388c-8d3c-472a-8055-ee7dba42d7a3" />

- Burada beklediğiniz 1-2 dk ekran değişmedi CTRL C ile durdurup. Aşağıdaki kodu tekrar girin. Sıra gelmesi lazım.

```bash
phase2cli contribute -c ethstorage-v1-trusted-setup-ceremony
```
