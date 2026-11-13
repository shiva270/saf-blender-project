# Instruksi kerja SAF Blender

## Sebelum setiap eksekusi Blender

1. Baca `README.md` dan konteks relevan di `percakapan.md`. Instruksi terbaru pengguna mengungguli keputusan lama dan panduan skill.
2. Baca `.agents/skills/blender-director/SKILL.md`, lalu `SKILL.md` spesialis yang relevan beserta referensi yang diperlukan, sebelum menjalankan batch operasi Blender. Sebutkan skill yang digunakan secara singkat kepada pengguna. Baca ulang bagian yang relevan ketika lingkup pekerjaan berubah.
3. Gunakan `.agents/skills/realistic-style/SKILL.md` untuk arah visual SAF. Pilih spesialis sesuai pekerjaan: `scene-assembly`, `hard-surface`, `materials`, `vehicle-artist`, `character-artist`, `animation`, atau lainnya. Semua skill tersedia; hanya skill relevan yang diterapkan agar konsep realistis tetap konsisten.
4. Periksa koneksi Blender MCP dan state scene aktual sebelum perubahan. Pertahankan edit pengguna. Buat backup sebelum perubahan besar atau destruktif. Jangan menganggap arsip percakapan membuktikan kondisi scene saat ini.
5. Gunakan `qa-review` untuk memverifikasi hasil visual dengan screenshot/render dan pemeriksaan yang relevan. Laporkan pekerjaan selesai, temuan terbuka, serta pemeriksaan yang belum dilakukan. Jangan mengklaim proyek sempurna atau selesai tanpa bukti.

## Keputusan desain yang harus dipertahankan

- Plant, perairan/perkapalan, dan bandara; lingkungan realistis, hijau, skala manusia. Poles draft dan manfaatkan aset detail pengguna.
- Dua tangki UCO horizontal, pompa dan common header. Pertemuan feed kerosene–UCO di atas vessel/support SAF; inlet reaktor elbow atas lalu turun vertikal.
- Reaktor → HP Separator → HP Stripper. Top HP Stripper → Fuel Gas; bottom → LP Stripper. Top LP Stripper → Naphtha/CDU II; bottom → tangki SAF.
- Tangki SAF terpisah jauh dari proses untuk animasi; dermaga dekat tangki. Tangki → pompa P401 → dua loading arm.
- Equipment silver satin metallic; tangki putih; handrail kuning; support krem; baseplate dan pijakan tangga tangki hitam; label mengikuti lengkungan shell.
- Rangka sekeliling kolom CDU dihapus. Garis kuning lantai dihapus; marka berhenti dan STOP di pertigaan tetap sesuai permintaan berikutnya.
- Bandara memiliki empat tangki T-401–T-404 dalam susunan 2×2 dekat loading arm penerimaan.

## Sumber skill dan cakupan instalasi

Skill disalin dari https://github.com/arjun988/blender-skills ke `.agents/skills/`, termasuk referensi relatifnya. Lihat `docs/BLENDER_SKILLS.md` dan `third_party/blender-skills/LICENSE`.

Instalasi ini berada di tingkat proyek. Saat berpindah komputer atau sesi, buka/clone repository ini dan baca instruksi ini. Pemasangan skill tidak otomatis memasang atau menghubungkan addon Blender MCP.
