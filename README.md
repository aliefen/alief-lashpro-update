# alief-lashpro-update

Server update otomatis **ALIEF LASHING PRO** (PT. Alief Energy Utama).

Versi terbaru: **1.2.0** (20 November 2026).

| File | Isi |
|---|---|
| `alief_lashpro_update.json` | Berkas pemberitahuan update bertanda tangan digital (Ed25519): versi, catatan rilis, ukuran dan SHA-256 paket |
| `ALIEF_LASHPRO_Update_x.y.z.exe` | Paket update kecil (kode program, panduan, catatan rilis) untuk PC yang sudah terpasang ALIEF LASHING PRO |

Program memeriksa berkas json ini saat dibuka dan setiap 6 jam. Paket hanya dipasang bila tanda tangan sah,
ukuran dan SHA-256 cocok, dan versinya lebih baru. Lisensi, pengaturan dan proyek tidak berubah.

Jangan mengubah atau mengganti nama file di repo ini secara manual: satu karakter berubah membuat tanda tangan
tidak sah dan update ditolak. Untuk PC baru gunakan installer lengkap `ALIEF_LASHPRO_Setup_x.y.z.exe`.
