ini file kedua ku

open git
mkdir namaFolder

#membuat config
git config --global user.name "namamu"
git config --global user.email emailmu@gmail

#melihat email dan username
git config --list

#membuat file
#nama file sesuai branch
touch namafile.ekstensi (touch main.txt)

#membuka file text
notepad namafile.txt

#membuat inisiasi
git init

#commit file
git commmit -m "tulis isipesan buka dengan tanda petik ditutup tanda petik"

#mlihat apakah git sudah ditambahkan atau belum
git status

#melihat histori perubahan commit git
git log

#menambahkan semua kedalam git
git add .

#buat repo di github.com

#copy tulisan seprti ini di git dan paste di gitCMD git remote add origin https://github.com/Samuel-08/Full_Stack.git

#lihat status versi remote di git
git remote -v

#mengirim file ke server git dan brach git
git push -u origin main

#buat keygen dan tambah ke seting git
ssh-keygen -t rsa -C samuelchristoper555@gmail.com

#liat list log yg sudah fix
git log --pretty=oneline

#hapus commit
git reset --soft 3103f4924198e1f8dad4ac1297289a450d188037
