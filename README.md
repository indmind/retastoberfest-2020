# RETASTOBERFEST 2020 (HACKTOBERFEST 2020)

Kontribusi sesuatu di sini, kita buat web sederhana untuk mengenalkan hacktoberfest.

## Cara Kontribusi

1. Fork repository ini
2. Pull ke pc kalian
3. Buat branch baru
  `git checkout -b nama-branch-baru`
4. Buat perubahan terserah, bisa tambah file halaman foto dll
5. commit dan push
   1. `git add .`
   2. `git commit -m 'pesan terserah'`
   3. `git push origin nama-branch-baru`
6. buka github, buat pull request ke repo  ini
7. tunggu sampai aku merge
8. ulangi sampai 4x untuk mendapatkan kaos

## Cara Mensinkronkan Repo Fork dengan Repo Original

1. Tambahkan remote baru bernama *upstream* untuk repo utama
  `git remote add upstream https://github.com/indmind/retastoberfest-2020.git`
2. Pull perubahan dari repo original
  `git pull upstream`
3. Terapkan perubahan ke branch dimana kalian berada
  `git rebase upstream/main`
