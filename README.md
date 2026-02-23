# ✂️ Sistem Pangkas Rambut Arjuna - VERSI LENGKAP

## 🎉 FITUR BARU V2.0!

### ✨ Yang Baru:
1. ✅ **EDIT & HAPUS DATA** - Salah input bisa diperbaiki!
2. ✅ **UBAH USERNAME & PASSWORD** - Keamanan lebih baik!
3. ✅ **TAMPILAN LEBIH ELEGAN** - Modern & professional
4. ✅ **BISA ONLINE** - Akses via link di Chrome HP!
5. ✅ **ANIMASI SMOOTH** - User experience lebih baik

---

## 🚀 CARA MENGGUNAKAN

### A. Pakai Offline (Di Komputer/HP)
1. **Extract ZIP** ini
2. **Buka `index.html`** di browser
3. **Login** dan mulai pakai!

### B. Pakai Online (Akses via Link)
1. Baca file **`CARA-HOSTING-ONLINE.md`**
2. Pilih platform: GitHub Pages / Netlify / Firebase
3. Upload file
4. Dapat link permanen!
5. Share link ke tim

---

## 🔐 LOGIN DEFAULT

**Owner:**
- Username: `owner`
- Password: `owner123`
- Akses: Dashboard + Input Data + Pengaturan

**Pekerja:**
- Username: `pekerja`  
- Password: `pekerja123`
- Akses: Input Data + Pengaturan

---

## ✨ FITUR LENGKAP

### 💰 Input Pemasukan
- Customer Dewasa/Anak (auto calculate)
- Hari otomatis terisi
- Total pemasukan
- Keterangan
- **EDIT & HAPUS** data yang sudah disimpan

### 💸 Input Pengeluaran Harian
- Semua kategori lengkap
- Akomodasi, Listrik & PDAM, Investor, Kontrakan, Gaji, Kopi & Rokok
- Jumlah Pengeluaran, Titipan
- Keterangan
- **EDIT & HAPUS** data

### 📅 Pengeluaran Rutin Bulanan
- Input per bulan/tahun
- Semua kategori
- Auto update jika edit bulan yang sama

### 📊 Dashboard Owner
- Statistik real-time
- Rekap lengkap seperti Excel
- Filter bulan/tahun
- **Export Excel** format profesional
- Sidebar pengeluaran bulanan

### ⚙️ Pengaturan Akun
- **Ubah Username** - Ganti username sesuka hati
- **Ubah Password** - Keamanan lebih baik
- Konfirmasi password
- Berlaku untuk owner & pekerja

---

## 🎨 CARA EDIT DATA

### Edit Pemasukan/Pengeluaran:
1. Login (owner atau pekerja)
2. Pilih tab yang sesuai
3. Scroll ke bawah, lihat **"📋 Data..."**
4. Klik tombol **"✏️ Edit"** pada data yang mau diubah
5. Form akan terisi otomatis
6. Ubah data yang perlu
7. Klik **"💾 Update"**
8. Selesai!

### Hapus Data:
1. Klik tombol **"🗑️ Hapus"** pada data
2. Konfirmasi penghapusan
3. Data terhapus permanen

**Note:** Owner dan pekerja bisa edit/hapus data masing-masing!

---

## 🔒 CARA UBAH USERNAME & PASSWORD

1. Login ke sistem
2. Klik tombol **"⚙️"** (Settings) di navbar
3. Modal pengaturan akan terbuka
4. Isi:
   - Username Baru (opsional)
   - Password Baru
   - Konfirmasi Password
5. Klik **"💾 Simpan Perubahan"**
6. **PENTING**: Catat username & password baru!
7. Logout dan login lagi dengan kredensial baru

**Tips Keamanan:**
- Ganti password default segera
- Gunakan password yang kuat
- Jangan share password ke sembarang orang
- Catat di tempat aman

---

## 🌐 HOSTING ONLINE

### Kenapa Harus Online?
✅ Akses dari mana saja (rumah, toko, jalan)
✅ Pekerja bisa input dari HP mereka
✅ Tidak perlu kirim file bolak-balik
✅ Owner bisa monitoring real-time
✅ Satu link untuk semua orang

### Platform Hosting GRATIS:

**1. GitHub Pages** (Rekomendasi!)
- 100% gratis selamanya
- Unlimited bandwidth
- SSL otomatis
- Baca: `CARA-HOSTING-ONLINE.md`

**2. Netlify**
- Super cepat setup (2 menit!)
- Drag & drop
- Auto SSL

**3. Firebase**  
- Google platform
- Analytics built-in
- Performa tinggi

**Panduan lengkap ada di file: `CARA-HOSTING-ONLINE.md`**

---

## 📱 TIPS PAKAI DI HP

### Tambah ke Home Screen (Jadi Seperti App!)

**Android (Chrome):**
1. Buka web di Chrome
2. Tap ⋮ (3 titik)
3. **"Add to Home screen"**
4. Sekarang ada icon di home screen!

**iPhone (Safari):**
1. Buka web di Safari
2. Tap tombol Share
3. **"Add to Home Screen"**
4. Done!

### Manfaat Add to Home Screen:
✅ Akses cepat seperti app
✅ Full screen (tanpa address bar)
✅ Terasa seperti aplikasi native
✅ Offline ready

---

## 💾 BACKUP DATA

### Cara 1: Export Excel (Mudah!)
1. Login sebagai owner
2. Buka Dashboard
3. Klik **"📥 Export Excel"**
4. Simpan file Excel
5. Lakukan setiap minggu!

### Cara 2: Backup Browser Data
```javascript
// Buka Console (F12), paste ini:
const backup = {
    income: localStorage.getItem('arjuna_income'),
    expense_daily: localStorage.getItem('arjuna_expense_daily'),
    expense_monthly: localStorage.getItem('arjuna_expense_monthly'),
    users: localStorage.getItem('arjuna_users')
};
console.log(JSON.stringify(backup));
// Copy output dan save ke file .txt
```

---

## 🆘 TROUBLESHOOTING

### ❌ Data Hilang Setelah Clear Browser
**Penyebab:** Browser cache di-clear
**Solusi:** Backup rutin dengan Export Excel!
**Pencegahan:** Jangan clear browser data

### ❌ Lupa Password Baru
**Solusi:**
```javascript
// Console (F12):
localStorage.removeItem('arjuna_users');
// Refresh, password kembali ke default
```

### ❌ Data Tidak Sync Antar Device
**Ini Normal!** Data tersimpan lokal per browser.
**Solusi:** Gunakan 1 link online, akses dari device manapun

### ❌ Edit Tidak Muncul
**Solusi:** Refresh halaman (F5 atau pull to refresh)

### ❌ Tombol Edit/Hapus Tidak Ada
**Penyebab:** Belum ada data
**Solusi:** Input data dulu, baru muncul tombol

---

## 📂 STRUKTUR FILE

```
barbershop-arjuna-v2-FINAL/
├── index.html              ← Login page (ELEGAN & ANIMASI!)
├── input.html              ← Input + EDIT/HAPUS data
├── dashboard.html          ← Dashboard owner
├── logo.jpg                ← Logo Pangkas Rambut Arjuna
├── README.md               ← File ini
└── CARA-HOSTING-ONLINE.md  ← Panduan hosting lengkap!
```

---

## 🎯 PERBEDAAN DENGAN VERSI LAMA

| Fitur | V1 (Lama) | V2 (Baru) |
|-------|-----------|-----------|
| Edit Data | ❌ Tidak bisa | ✅ **BISA!** |
| Hapus Data | ❌ Tidak bisa | ✅ **BISA!** |
| Ubah Password | ❌ Manual via console | ✅ **Pakai Form!** |
| Tampilan | Bagus | ✅ **Lebih Elegan!** |
| Animasi | Standar | ✅ **Smooth & Modern!** |
| Hosting Online | Manual | ✅ **Ada Panduan!** |
| Font | Default | ✅ **Poppins (Modern)!** |

---

## 🏆 BEST PRACTICES

### Harian:
1. ✅ Input data sebelum tutup toko
2. ✅ Cek rekap di dashboard
3. ✅ Pastikan data tersimpan

### Mingguan:
1. ✅ **Export Excel** untuk backup
2. ✅ Review pengeluaran
3. ✅ Analisa pemasukan

### Bulanan:
1. ✅ Input pengeluaran rutin bulanan
2. ✅ Cek keuntungan total
3. ✅ Backup file Excel ke cloud

### Keamanan:
1. ✅ **Ganti password default**
2. ✅ Jangan share password
3. ✅ Logout setelah pakai
4. ✅ Simpan backup di tempat aman

---

## 🎨 CUSTOMISASI

### Ganti Logo:
1. Replace file `logo.jpg` dengan logo baru
2. Ukuran rekomendasi: 500x500px
3. Format: JPG atau PNG
4. Upload ulang jika online

### Tambah User Baru:
```javascript
// Console (F12):
let users = JSON.parse(localStorage.getItem('arjuna_users'));
let newId = Math.max(...users.map(u => u.id)) + 1;
users.push({
    id: newId,
    username: 'pekerja2',
    password: 'password123',
    role: 'worker',
    name: 'Pekerja 2'
});
localStorage.setItem('arjuna_users', JSON.stringify(users));
alert('User baru ditambahkan!');
```

---

## 📊 DATA FORMAT

### Penyimpanan:
- **LocalStorage** (browser)
- **Format:** JSON
- **Keys:**
  - `arjuna_income` - Data pemasukan
  - `arjuna_expense_daily` - Pengeluaran harian
  - `arjuna_expense_monthly` - Pengeluaran bulanan
  - `arjuna_users` - Data user

### Export Excel:
- Format: `.xlsx`
- Include: Semua data sesuai filter
- Siap print!

---

## 🔄 UPDATE SISTEM

### Jika Ada Update Baru:
1. Download versi baru
2. Backup data (Export Excel)
3. Replace semua file
4. Upload ulang jika online
5. Data tetap aman (di browser)

---

## 📞 SUPPORT & BANTUAN

### Jika Ada Masalah:
1. ✅ Baca README ini lengkap
2. ✅ Cek TROUBLESHOOTING
3. ✅ Baca CARA-HOSTING-ONLINE.md
4. ✅ Clear cache dan coba lagi

### Tips:
- Gunakan browser modern (Chrome, Firefox, Edge)
- Update browser ke versi terbaru
- Pastikan JavaScript enabled
- Gunakan koneksi internet stabil (untuk hosting)

---

## 🎉 KESIMPULAN

### Sistem Ini Cocok Untuk:
✅ Barbershop kecil-menengah
✅ Yang ingin digitalisasi pencatatan
✅ Yang butuh edit/hapus data
✅ Yang ingin akses dari HP
✅ Yang butuh backup mudah
✅ Budget terbatas (GRATIS!)

### Keunggulan:
✅ **Mudah digunakan** - Interface intuitif
✅ **Lengkap** - Semua fitur ada
✅ **Modern** - Tampilan elegan
✅ **Flexible** - Edit/hapus data
✅ **Portable** - Bisa offline & online
✅ **Aman** - Data lokal, no server
✅ **Gratis** - 100% free!

---

**Selamat Menggunakan! 🎊✂️**

**Pangkas Rambut Arjuna**
**Est. 2020 - Now Digital!**

Made with ❤️ for modern barbershop management
