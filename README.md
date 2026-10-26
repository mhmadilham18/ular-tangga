# Ular Tangga Edukasi

Game ular tangga untuk kelas. Pemain melempar dadu, menjawab kartu misi, lalu naik tangga atau turun ular.

## Cara Pakai

1. Buka `index.html` di browser (perlu internet untuk font dan impor Excel).
2. Klik **MAIN BARU**.
3. Isi pemain, kartu misi, dan aturan.
4. Klik **MULAI MAIN**.

## Fitur

- Sampai 40 pemain
- Papan 6x6, 8x8, atau 10x10
- Preset jenjang SD, SMP, SMA
- 1 atau 2 dadu (kembar = main lagi)
- Kartu misi dengan jawaban dan timer opsional
- Impor kartu dari Excel
- Sesi tersimpan otomatis di browser

## Aturan Singkat

- Mendarat di kaki tangga naik, di kepala ular turun.
- Harus pas di kotak terakhir, kelebihan langkah akan memantul mundur.
- Jawaban benar: +1 bintang (dan maju 2 kotak jika opsi bonus aktif).
- Selesai saat ada pemenang, atau lanjut sampai semua selesai.

## Format Excel

Sheet pertama, dengan header:

| misi      | jawaban |
| --------- | ------- |
| 7 x 8 = ? | 56      |

Template bisa diunduh dari langkah **MISI**.

## Sesi Tersimpan

Disimpan di localStorage browser dan berlaku 24 jam. Lanjutkan dari beranda lewat tombol **LANJUTKAN**. Sesi tidak pindah antar browser atau perangkat.

## Kontrol

- Spasi atau Enter: lempar dadu
- Esc: tutup popup
