## PySemut-AI

### Simulasi Semut ditulis dalam Python

Ini adalah simulasi jejak feromon semut yang ditulis dalam Python3, menggunakan Pygame2 dan Numpy.

**Cara Menggunakan:**
Simpan file `nants.py` di suatu tempat, lalu jalankan melalui Python.  
(Contoh perintah menjalankan: `python3 nants.py`)

Klik kiri pada mouse untuk meletakkan makanan, klik kanan untuk menghapus makanan.

Tekan tombol `Esc` untuk keluar.

Beberapa pengaturan yang dapat diubah di bagian atas kode. Kamu dapat menyesuaikan ukuran jendela, layar penuh, FPS, dan jumlah semut yang ingin kamu munculkan. Rasio resolusi piksel pada permukaan jejak feromon juga dapat diubah, meskipun hal ini akan memengaruhi cara kerja logika pencarian jalur mereka.

**Daftar hal-hal yang perlu diperbaiki/dilaksanakan:**
- Menghindari rintangan/dinding, terutama saat menuju sarang.
- Partikel makanan belum bisa diambil/dihapus saat semut 'mengambil' mereka.

---

        Program ini adalah perangkat lunak bebas: kamu dapat mendistribusikan ulang
        atau memodifikasinya di bawah ketentuan GNU General Public License yang diterbitkan oleh
        Free Software Foundation.

        Program ini didistribusikan dengan harapan dapat berguna,
        tetapi TANPA JAMINAN; bahkan tanpa jaminan tersirat
        DIPERDAGANGKAN atau KESESUAIAN UNTUK TUJUAN TERTENTU.  Lihat
        GNU General Public License untuk detail lebih lanjut.

        Kamu seharusnya telah menerima salinan GNU General Public License
        bersama program ini. Jika tidak, lihat: https://www.gnu.org/licenses/gpl-3.0.html


