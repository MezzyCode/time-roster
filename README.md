# time-roster-app

Time roster merupakan aplikasi berbasis web yang membantu para pengguna untuk memanagemen waktu mereka secara efisien dimanapun dan kapanpun.

## Command

`npm install` untuk memasang seluruh dependencies yang digunakan pada proyek.

`npm run start-dev` Menjalankan proyek pada mode development menggunakan webpack-dev-server.

`npm run build` Membangun proyek dalam mode production.

## How to Use

### Menambahkan jadwal

1. Login menggunakan akun google
2. Menuju halaman **Main app**
3. Klik `Add task`
4. Isi form yang muncul
5. Klik submit

### Mengedit atau menghapus jadwal

1. Login menggunakan akun google
2. Menuju halaman **Main app**
3. Klik `Add task`
   * Isi form yang muncul untuk mengubah jadwal
   * atau bila ingin menghapus klik `delete`
4. Klik submit

Jadwal yang ditambahkan, diedit, atau dihapus akan tersimpan dalam akun google yang terhubung.

### Tips dan Warning

User dapat meng-click tombol info yang ada di samping nama kuadran untuk mendapatkan info tentang task apa saja yang baik dimasukan ke dalam kuadran.
Jika user memiliki time management yang buruk, misal :

* Memiliki task di kuadran Important and Urgent yang terlalu banyak
* Memasukan task ke kuadran Imporant tanpa menjadwalkan task
Hal ini akan menimbulkan Warning di kuadran yang ditentukan.

Firebase prototype:
<https://github.com/leafAlif/time-roster-backend>
