# ✂️ Pangkas Rambut Arjuna - Sistem Pencatatan Keuangan v2

## 🎉 VERSI TERBARU - LANGSUNG PAKAI!

### ✨ Fitur Baru di Versi 2:

- ✅ **Edit & Hapus Data** - Salah input? Bisa diedit/hapus!
- ✅ **Ubah Username & Password** - Pengaturan akun lengkap
- ✅ **Tampilan Lebih Elegant** - Design modern & profesional
- ✅ **100% Mobile Responsive** - Perfect di HP, tidak terpotong!
- ✅ **Input Lebih Simple** - Pekerja hanya input pemasukan + akomodasi
- ✅ **Owner Input Lengkap** - Semua pengeluaran bulanan di dashboard

---

## 🚀 Cara Menggunakan

1. **Extract ZIP**
2. **Buka `index.html`**
3. **Login** dan pakai!

**Tidak perlu install apapun!** ✅

---

## 🔐 Login Default

### Owner:
- Username: `owner`
- Password: `owner123`
- **Akses**: Dashboard, Input, Settings, Export Excel

### Pekerja:
- Username: `pekerja`
- Password: `pekerja123`
- **Akses**: Input Pemasukan & Akomodasi, Settings

---

## 📱 Akses dari HP

### Dijamin Tidak Terpotong!
- ✅ Logo tampil sempurna
- ✅ Navbar responsive
- ✅ Tabel scroll horizontal
- ✅ Form input nyaman
- ✅ Tombol mudah diklik

### Cara:
1. Copy folder ke HP
2. Buka `index.html` dengan browser
3. Login dan pakai!

---

## 🌟 Fitur Lengkap

### Untuk Pekerja:

**Input Harian:**
- 👨 Customer Dewasa
- 👶 Customer Anak
- 👥 Total (otomatis)
- 💰 Total Pemasukan
- 🏠 Akomodasi
- 📝 Keterangan

**Fitur Edit/Hapus:**
- ✏️ Edit data yang salah
- 🗑️ Hapus data duplikat
- 📋 Lihat data hari ini

**Settings:**
- 🔐 Ubah username sendiri
- 🔒 Ubah password sendiri

### Untuk Owner:

**Dashboard Lengkap:**
- 📊 Statistik real-time:
  - 💰 Total Pemasukan
  - 💸 Total Pengeluaran
  - 📈 Keuntungan
  - 👥 Total Customer
- 📅 Filter per bulan/tahun
- ✏️ Edit semua data
- 🗑️ Hapus data salah

**Input Pengeluaran Bulanan:**
- Listrik & PDAM
- Investor
- Kontrakan
- Gaji
- Ridwan
- Auto calculate total

**Export Excel:**
- 📥 Download laporan lengkap
- Format profesional
- Include pengeluaran bulanan
- Siap print!

---

## ✨ Tampilan Modern

**Design Highlights:**
- 🎨 Gradient modern
- 📱 100% Mobile responsive
- 🖼️ Logo branding di semua halaman
- 💫 Smooth animations
- 🎯 Clean & minimalist
- ⚡ Fast loading

**Font:** Inter - Professional & modern

**Color Scheme:**
- Primary: Purple gradient (#667eea → #764ba2)
- Success: Green (#10b981)
- Danger: Red (#ef4444)
- Info: Blue (#3b82f6)

---

## 🔧 Cara Edit/Hapus Data

### Dari Pekerja (Data Hari Ini):
1. Scroll ke "Data Hari Ini"
2. Klik **✏️ Edit** untuk ubah
3. Atau klik **🗑️ Hapus** untuk delete
4. Konfirmasi dan selesai!

### Dari Owner (Semua Data):
1. Buka Dashboard
2. Pilih bulan/tahun
3. Klik **✏️** pada data yang ingin diedit
4. Form otomatis terisi, edit, dan save
5. Atau klik **🗑️** untuk hapus langsung

---

## ⚙️ Cara Ubah Username/Password

1. Klik tombol **⚙️** di navbar
2. Pilih:
   - **Ubah Username**: Masukkan username baru
   - **Ubah Password**: Masukkan password lama → password baru
3. Klik **Simpan**
4. Selesai!

**Note:** Setiap user bisa ubah akun sendiri

---

## 💾 Backup & Restore

### Backup (Cara Mudah):
- Klik **Export Excel** setiap minggu
- File Excel = backup data Anda

### Backup (Advanced):
```javascript
// Buka Console (F12):
const backup = {
    income: localStorage.getItem('arjuna_income'),
    users: localStorage.getItem('arjuna_users'),
    monthly: localStorage.getItem('arjuna_expense_monthly')
};
console.log(JSON.stringify(backup));
// Copy output dan save ke .txt
```

### Restore:
```javascript
// Paste backup data:
localStorage.setItem('arjuna_income', '...');
localStorage.setItem('arjuna_users', '...');
localStorage.setItem('arjuna_expense_monthly', '...');
// Refresh halaman
```

---

## 📊 Perbedaan Versi 1 vs Versi 2

| Fitur | Versi 1 | Versi 2 |
|-------|---------|---------|
| Edit Data | ❌ | ✅ |
| Hapus Data | ❌ | ✅ |
| Ubah Password | ❌ | ✅ |
| Mobile Responsive | Partial | ✅ Perfect |
| Logo di HP | Terpotong | ✅ Perfect |
| Tampilan | Good | ✅ Elegant |
| Font | System | ✅ Inter |
| Settings Page | ❌ | ✅ |
| Pekerja Input | Semua | ✅ Simple |
| Owner Input Bulanan | Tab | ✅ Dashboard |

---

## 🆘 Troubleshooting

### ❌ Logo Tidak Muncul
**Solusi:** Normal, logo optional. Sistem tetap jalan.

### ❌ Data Hilang
**Solusi:** 
- Jangan clear browser data
- Backup rutin dengan Export Excel

### ❌ Salah Input
**Solusi:**
- Klik **✏️ Edit** untuk ubah
- Atau **🗑️ Hapus** lalu input ulang

### ❌ Lupa Password
**Solusi:**
```javascript
// Console (F12):
let users = JSON.parse(localStorage.getItem('arjuna_users'));
users[0].password = 'passwordbaru'; // owner
users[1].password = 'passwordbaru'; // pekerja
localStorage.setItem('arjuna_users', JSON.stringify(users));
// Refresh
```

### ❌ Edit Tidak Berfungsi
**Solusi:**
- Pastikan browser support localStorage
- Coba browser lain (Chrome/Firefox)

---

## 📂 Struktur File

```
pangkas-rambut-arjuna-v2/
├── index.html          ← Login (START HERE!)
├── input.html          ← Input data pekerja
├── dashboard.html      ← Dashboard owner
├── settings.html       ← Ubah username/password
├── logo.jpg            ← Logo Pangkas Rambut Arjuna
└── README.md           ← File ini
```

**Total:** 5 file HTML + 1 logo + 1 README = Siap pakai!

---

## 🎯 Best Practices

1. **Input Harian** - Sebelum tutup toko
2. **Export Excel** - Setiap minggu (backup otomatis)
3. **Backup File** - Simpan ke Google Drive/Flashdisk
4. **Ganti Password** - Setelah install pertama kali
5. **Cek Dashboard** - Setiap hari untuk monitoring
6. **Update Bulanan** - Input pengeluaran rutin setiap awal bulan

---

## 🔒 Keamanan

- ✅ Data tersimpan **lokal** di browser
- ✅ **Tidak ada server** eksternal
- ✅ **100% offline** (kecuali export Excel)
- ✅ Password bisa diubah sendiri
- ✅ Setiap user punya akun sendiri
- ✅ Tidak ada tracking/analytics

---

## 💡 Tips & Trik

### Untuk Pekerja:
- Input langsung setelah selesai potong rambut
- Cek "Data Hari Ini" sebelum pulang
- Edit kalau ada yang salah, jangan input ulang

### Untuk Owner:
- Cek dashboard setiap pagi
- Export Excel setiap akhir minggu
- Input pengeluaran bulanan di awal bulan
- Backup file Excel ke cloud storage

### Untuk Semua:
- Ubah password default segera
- Jangan share password
- Jangan clear browser data
- Selalu backup sebelum format HP/Laptop

---

## 📱 Mobile Features

**Optimasi Khusus HP:**
- ✅ Touch-friendly buttons (44px minimum)
- ✅ Swipe untuk scroll tabel
- ✅ Auto-zoom disabled pada input
- ✅ Navbar sticky (tidak hilang saat scroll)
- ✅ Logo scaled perfect
- ✅ Font size readable
- ✅ Form fields besar & mudah diklik

**Tested on:**
- ✅ Android Chrome
- ✅ iPhone Safari
- ✅ Samsung Internet
- ✅ Opera Mobile

---

## 🚀 Upgrade dari Versi 1

**Data TIDAK otomatis pindah!**

Jika Anda pakai Versi 1:
1. Export Excel dari Versi 1
2. Input manual ke Versi 2
3. Atau copy localStorage:
   ```javascript
   // Di Versi 1:
   localStorage.getItem('barbershop_income')
   // Copy output
   
   // Di Versi 2:
   localStorage.setItem('arjuna_income', '...')
   ```

---

## 🎨 Customization

### Ganti Warna Tema:
Edit file HTML → Cari `#667eea` dan `#764ba2` → Ganti dengan warna favorit

### Ganti Logo:
Replace file `logo.jpg` dengan logo Anda (ukuran: 500x500px optimal)

### Tambah User:
```javascript
let users = JSON.parse(localStorage.getItem('arjuna_users'));
users.push({
    id: 3,
    username: 'pekerja2',
    password: 'password123',
    role: 'worker',
    name: 'Pekerja 2'
});
localStorage.setItem('arjuna_users', JSON.stringify(users));
```

---

## 📞 Support

Jika ada pertanyaan:
1. Baca README ini teliti
2. Cek section Troubleshooting
3. Test di browser berbeda
4. Hubungi developer

---

## 🏆 Keunggulan Sistem

✅ **Zero Setup** - Langsung pakai
✅ **Edit & Delete** - Fleksibel
✅ **Mobile Perfect** - Tidak terpotong
✅ **Elegant Design** - Professional
✅ **Fast & Light** - Load instant
✅ **Offline First** - Tidak butuh internet
✅ **Secure** - Data lokal Anda
✅ **Free Forever** - 100% gratis
✅ **No Ads** - Clean interface
✅ **Privacy** - Zero tracking

---

## 📝 Changelog

### Version 2.0 (Latest)
- ✅ Fitur Edit & Hapus data
- ✅ Settings untuk ubah username/password
- ✅ Tampilan modern dengan font Inter
- ✅ 100% Mobile responsive
- ✅ Logo perfect di semua device
- ✅ Input pekerja disederhanakan
- ✅ Owner input bulanan di dashboard
- ✅ Smooth animations
- ✅ Better UX/UI

### Version 1.0
- Input pemasukan & pengeluaran
- Dashboard basic
- Export Excel
- Login system

---

**Made with ❤️ for Pangkas Rambut Arjuna**

**Est. 2020 - System v2.0 (2026)**

---

**Selamat Menggunakan! ✂️💈**
