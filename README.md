# Space Shooter Game 🚀

Space Shooter adalah game sederhana yang dibuat menggunakan Pygame, di mana pemain mengendalikan pesawat ruang angkasa untuk menembak musuh dan UFO.

## 📝 Deskripsi

Tujuan dari game ini adalah untuk menghindari peluru musuh dan menghancurkan UFO sebanyak mungkin sambil menjaga agar pesawat tetap aman.

### Fitur Utama
* Kontrol penuh pesawat pemain menggunakan mouse
* Sistem tembakan dengan efek suara
* Latar belakang luar angkasa yang menarik
* Efek suara untuk tembakan dan ledakan
* Musuh acak dengan AI sederhana untuk bergerak dan menembak

## 🛠️ Prasyarat

Sebelum memulai, pastikan sistem Anda memiliki:
* Python
* Pygame

Untuk menginstal Pygame, gunakan perintah berikut:
```bash
pip install pygame
```

## 📁 File yang Dibutuhkan

Pastikan Anda memiliki file aset berikut dan menempatkannya di direktori yang sesuai:

| File | Deskripsi |
|------|-----------|
| `plyship.png` | Gambar pesawat pemain |
| `enemyship.png` | Gambar pesawat musuh |
| `ufo.png` | Gambar UFO |
| `pbullet.png` | Peluru pemain |
| `enemybullet.png` | Peluru musuh |
| `space_background.jpg` | Latar belakang ruang angkasa |
| `shoot.wav` | Suara tembakan |
| `explosion.wav` | Suara ledakan |

## ⚙️ Konfigurasi

Sebelum menjalankan game, ganti path file berikut sesuai lokasi di komputer Anda:

```python
player_ship = 'D:/Game/plyship.png'
enemy_ship = 'D:/Game/enemyship.png'
ufo_ship = 'D:/Game/ufo.png'
player_bullet = 'D:/Game/pbullet.png'
enemy_bullet = 'D:/Game/enemybullet.png'
ufo_bullet = 'D:/Game/enemybullet.png'
background_image = 'D:/Game/space_background.jpg'
shoot_sound = 'D:/Game/shoot.wav'
explosion_sound = 'D:/Game/explosion.wav'
```

## 🎮 Cara Menjalankan

1. Buka terminal atau command prompt
2. Arahkan ke direktori yang berisi file `main.py`
3. Jalankan perintah:
```bash
python main.py
```

## 🕹️ Kontrol Permainan

* **Mouse**: Menggerakkan pesawat
* **Spasi**: Menembak
* **ESC**: Keluar dari permainan

## 📝 Lisensi

[MIT License](LICENSE)

## 👥 Kontribusi

Kontribusi selalu diterima! Jangan ragu untuk membuka issue atau pull request.

## 📧 Kontak

Jika Anda memiliki pertanyaan, silakan hubungi viananto1234@gmail.com.
