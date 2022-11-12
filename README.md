<p style="font-size:14px" align="right">
<a href="https://t.me/bangpateng_group" target="_blank">Join our telegram <img src="https://user-images.githubusercontent.com/50621007/183283867-56b4d69f-bc6e-4939-b00a-72aa019d1aea.png" width="30"/></a>
<a href="https://bangpateng.com/" target="_blank">Visit our website <img src="https://user-images.githubusercontent.com/38981255/184068977-2d456b1a-9b50-4b75-a0a7-4909a7c78991.png" width="30"/></a>
</p>

<p align="center">
  <img height="150" height="auto" src="https://user-images.githubusercontent.com/38981255/185994172-0b4e4ea8-f81a-48db-8020-9be619f485b7.png">
</p>

# ALEO PROVER TESTNET INCENTIVIZED

##  1. Ikhtisar

__snarkOS__ adalah sistem operasi terdesentralisasi untuk aplikasi pribadi. Ini membentuk tulang punggung [ Aleo ](https://aleo.org/) dan
memungkinkan aplikasi untuk memverifikasi dan menyimpan status dengan cara yang dapat diverifikasi secara publik.

## 2. Spesifiksi Minimal

Berikut adalah persyaratan **minimum** untuk menjalankan node Aleo:

 -  **CPU** : 16-core (lebih disukai 32-core)
 -  **RAM** : Memori 16GB (lebih disukai 32GB)
 -  **Penyimpanan** : 128GB ruang disk
 -  **Jaringan** : 50 Mbps upload **dan** bandwidth download

# Instal Otomatis Bro

```
wget -O prover.sh https://raw.githubusercontent.com/bangpateng/Aleo-Prover/main/prover.sh && chmod +x prover.sh && ./prover.sh
```

Biarkan Instalisasi Selesai Lama Kudu Sabar dan Jangan Lupa Backup Semua Data Kalian Yang Muncul, Setelah Instalisasi Otomatis

# Run Prover

```
screen -r prover
```

```
./run-prover.sh
```
- `ctrl A D` untuk Menyimpan Screen Agar Jalan di Background Pc Kalian
- Masukan Private Key Yang Sudah Kalian Backup Sebelumnya. Jika anda Ingin Kembali ke Screen Yang Sedang Jalan, Gunakan Perintah `screen -Rd prover`

## Uninstal (Gunakan Jika Mau Menghapus Data Node)

```
rustup self uninstall
rm -rf prover.sh
rm -rf snarkOS
```
