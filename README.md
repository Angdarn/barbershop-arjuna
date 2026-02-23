# ✂️ Sistem Pencatatan Keuangan - Pangkas Rambut Arjuna

## 🎉 LANGSUNG PAKAI - TANPA INSTALASI!

### 🚀 Cara Menggunakan (Super Mudah!)

1. **Extract file ZIP** ini
2. **Double-click `index.html`** 
3. **Login** dan mulai pakai!

**Selesai!** Tidak perlu install Node.js, tidak perlu setup server! ✅

---

## 🔐 Login Default

### Owner (Pemilik):
- **Username**: `owner`
- **Password**: `owner123`
- **Akses**: Dashboard + Input Data

### Pekerja:
- **Username**: `pekerja`
- **Password**: `pekerja123`
- **Akses**: Input Data

---

## 🌟 Fitur Lengkap

### ✅ Input Data (Untuk Pekerja)

**Pemasukan Harian:**
- Customer Dewasa
- Customer Anak
- Jumlah Total Otomatis
- Total Pemasukan (Rp)
- Hari otomatis terisi
- Keterangan

**Pengeluaran Harian:**
- Akomodasi
- Listrik & PDAM
- Investor
- Kontrakan
- Gaji
- Kopi & Rokok
- Jumlah Pengeluaran
- Titipan
- Keterangan

**Pengeluaran Rutin Bulanan:**
- Akomodasi Barber
- Listrik & PDAM
- Investor
- Kontrakan
- Gaji
- Ridwan

### 📊 Dashboard (Untuk Owner)

**Statistik Real-time:**
- 💰 Total Pemasukan
- 💸 Total Pengeluaran
- 📊 Keuntungan
- 👥 Total Customer

**Rekap Harian:**
- Tabel lengkap dengan format seperti Excel
- Semua data pemasukan & pengeluaran
- Total otomatis per kategori
- Sidebar pengeluaran bulanan

**Export Excel:**
- Download laporan lengkap
- Format profesional
- Include pengeluaran bulanan
- Siap print!

---

## 📱 Akses dari HP

### Cara 1: Copy File ke HP
1. Copy seluruh folder ke HP via:
   - USB kabel
   - WhatsApp
   - Google Drive
   - Email
2. Buka file `index.html` dengan browser di HP
3. Login dan pakai!

### Cara 2: Upload ke Cloud
Upload ke Google Drive, lalu akses link dari HP

---

## 💾 Keamanan Data

- ✅ Data tersimpan **lokal** di browser (localStorage)
- ✅ **Tidak ada server eksternal**
- ✅ **100% offline** (tidak butuh internet)
- ✅ Data aman di device Anda

---

## 📥 Backup Data

### Backup Manual via Export:
- Buka Dashboard
- Klik "Export Excel" setiap minggu
- File Excel bisa jadi backup

### Backup Browser Data:
```javascript
// Buka Console (F12), copy paste ini:
const backup = {
    income: localStorage.getItem('arjuna_income'),
    expense_daily: localStorage.getItem('arjuna_expense_daily'),
    expense_monthly: localStorage.getItem('arjuna_expense_monthly')
};
console.log(JSON.stringify(backup));
// Copy hasil output dan save ke file .txt
```

---

## 🔧 Ganti Password

1. Buka Console browser (tekan F12)
2. Paste script ini:

```javascript
let users = JSON.parse(localStorage.getItem('arjuna_users'));
users[0].password = 'passwordbaru123'; // owner
users[1].password = 'passwordbaru456'; // pekerja
localStorage.setItem('arjuna_users', JSON.stringify(users));
alert('Password berhasil diganti!');
```

---

## 🆘 Troubleshooting

### ❌ Data Hilang Setelah Clear Browser
**Penyebab**: Browser cache di-clear
**Solusi**: Backup rutin dengan Export Excel!

### ❌ File Tidak Bisa Dibuka
**Solusi**: 
- Extract ZIP dulu
- Jangan buka dari dalam ZIP
- Buka dengan browser modern (Chrome, Firefox, Edge)

### ❌ Lupa Password
**Solusi**:
```javascript
// Buka Console (F12):
localStorage.removeItem('arjuna_users');
// Refresh halaman, password kembali ke default
```

### ❌ Export Excel Tidak Jalan
**Penyebab**: Library butuh internet untuk load
**Solusi**: Pastikan ada koneksi internet saat export

---

## 📂 Struktur File

```
pangkas-rambut-arjuna/
├── index.html          ← Halaman Login (BUKA INI DULU!)
├── input.html          ← Input Data Pekerja
├── dashboard.html      ← Dashboard Owner
├── logo.jpg            ← Logo Pangkas Rambut Arjuna
└── README.md           ← File ini
```

---

## 🎯 Tips Penggunaan

### 💡 Multi-Device
Copy folder ke Google Drive, akses dari mana saja!

### 💡 Backup Rutin
Export Excel setiap minggu sebagai backup otomatis

### 💡 Mobile Friendly
Tampilan sudah responsive, nyaman di HP!

### 💡 Offline First
Tidak butuh internet kecuali saat export Excel

---

## ⚙️ Format Rekap

Sistem ini mengikuti format rekap yang sudah Anda gunakan:

✅ Kolom Customer (Dewasa/Anak/Jumlah)
✅ Hari otomatis
✅ Income Harian
✅ Pengeluaran Harian (semua kategori)
✅ Jumlah Pengeluaran Harian
✅ Titipan
✅ Keterangan
✅ Total otomatis
✅ Pengeluaran Rutin Bulanan (sidebar)

---

## 🎨 Tampilan

- **Tema**: Merah & Biru (sesuai branding barbershop)
- **Logo**: Pangkas Rambut Arjuna di navbar
- **Modern**: Gradient & shadow effects
- **Professional**: Clean & easy to use

---

## 📊 Perbedaan dengan Sistem Lama

| Fitur | Manual Excel | Sistem Baru |
|-------|-------------|-------------|
| Input | Ketik manual | Form otomatis |
| Perhitungan | Manual | Otomatis |
| Total | Hitung sendiri | Auto calculate |
| Backup | Copy file | Export Excel |
| Multi-user | Sulit | Mudah (copy ke HP) |
| Hari | Ketik manual | Otomatis |
| Customer Total | Hitung manual | Otomatis |

---

## 🔄 Update & Maintenance

### Tambah User Baru:
```javascript
let users = JSON.parse(localStorage.getItem('arjuna_users'));
users.push({
    username: 'pekerja2',
    password: 'password123',
    role: 'worker',
    name: 'Pekerja 2'
});
localStorage.setItem('arjuna_users', JSON.stringify(users));
```

### Reset Semua Data:
```javascript
localStorage.clear();
// Refresh halaman
```

---

## 📞 Support

Jika ada pertanyaan atau butuh bantuan:
1. Baca README ini dengan teliti
2. Cek section Troubleshooting
3. Hubungi developer

---

## 🎉 Kelebihan Sistem Ini

✅ **Langsung pakai** - Zero setup
✅ **Simple** - UI intuitif
✅ **Cepat** - Load instant
✅ **Offline** - Tidak butuh internet
✅ **Portable** - Bisa di HP, laptop, flashdisk
✅ **Gratis** - 100% free
✅ **Aman** - Data lokal Anda
✅ **Professional** - Export ke Excel
✅ **Branded** - Logo Pangkas Rambut Arjuna
✅ **Modern** - Tampilan menarik

---

## 📝 Catatan Penting

⚠️ **JANGAN hapus folder/file** - Sistem butuh semua file
⚠️ **BACKUP rutin** - Export Excel setiap minggu
⚠️ **JANGAN clear browser** - Data bisa hilang
⚠️ **GANTI password** - Untuk keamanan

---

## 🏆 Best Practices

1. **Input harian** sebelum tutup toko
2. **Export Excel** setiap Minggu
3. **Backup file Excel** ke cloud/flashdisk
4. **Ganti password** berkala
5. **Cek rekap** setiap akhir bulan

---

**Selamat Menggunakan! ✂️**

**Pangkas Rambut Arjuna - Est. 2020**

Made with ❤️ for Pangkas Rambut Arjuna
