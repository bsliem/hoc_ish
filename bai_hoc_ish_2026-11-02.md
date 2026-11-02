# HOC iSH TREN iPAD
## Ngay 02/11/2026

## 1. Terminal Linux

pwd                 # Vi tri hien tai
ls -la              # Liet ke tap tin
mkdir hoc_ish       # Tao thu muc
cd hoc_ish          # Vao thu muc
cd ..               # Len thu muc cha
cd ~                # Ve thu muc home

## 2. Quan ly tap tin

echo "A Di Da Phat" > niem_phat.txt
echo "Hoc Linux" >> niem_phat.txt
cat niem_phat.txt

mkdir kinh_phat
cp niem_phat.txt kinh_phat/

## 3. Cai Git

apk update
apk add git openssh-client
git --version

## 4. Cau hinh Git

git config --global user.name "iPad"
git config --global user.email "liem20k@gmail.com"

## 5. SSH GitHub

ssh-keygen -t ed25519 -C "iSH-iPad"
cat ~/.ssh/id_ed25519.pub
ssh -T git@github.com

Ket qua:
Hi bsliem! You've successfully authenticated.

## 6. Git co ban

git init
git branch -M main
git add .
git commit -m "[iPad] Bai hoc Linux"
git status

## 7. Ket noi GitHub

git remote add origin git@github.com:bsliem/hoc_ish.git
git push -u origin main

## 8. Loi da gap

- cd ho_ish: go sai ten thu muc.
- cat file: file chua duoc tao.
- git add.: thieu dau cach.
- nothing to commit: khong co thay doi moi.
- No configured push destination: thieu remote.

## 9. Ghi nho

>  : Ghi de tap tin
>> : Ghi them vao cuoi tap tin
cp : Copy
cd : Change directory
pwd: Print working directory

## 10. Bai hoc tiep theo

- Nano va Vi
- Shell Script
- Python
- Tao lenh gp de push GitHub tu dong
