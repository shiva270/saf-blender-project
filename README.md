# SAF Blender Project

Arsip keputusan desain dan audit visualisasi rantai SAF: kilang, perairan/perkapalan, dan bandara.

> Ringkasan percakapan, bukan transkrip lengkap. Snapshot 14 November 2026. Auto-sync belum aktif.

## Konsep

Video.pptx: slide 1 alur hulu-hilir; slide 2 lineup SAF; slide 3 interior reaktor. Arahan terbaru pengguna mengungguli diagram lama. Model realistis dengan skala manusia, lingkungan hijau, dan aset detail pengguna.

Equipment silver satin metallic; tanki putih; handrail/tangga kuning; support krem; baseplate dan pijakan tangga tanki hitam. Label silinder mengikuti lengkungan.

## Lineup final yang diminta

- UCO: dua tanki horizontal dengan pompa dan common feed header.
- Feed kerosene + UCO bertemu pada line besar di atas vessel/support SAF agar aliran terlihat.
- Inlet reaktor berupa elbow atas lalu turun vertikal ke nozzle.
- Reaktor -> HP Separator -> HP Stripper.
- Top HP Stripper -> Fuel Gas; bottom -> LP Stripper.
- Top LP Stripper -> Naphtha to CDU II; bottom -> SAF storage.
- Tanki SAF berjauhan dari plant untuk animasi aliran.
- Tanki -> pompa transfer P401 -> dua loading arm dermaga.

## Kilang dan marine

CDU memiliki kolom utama mencolok. Frame sekeliling kolom dihapus sesuai permintaan. Furnace stack metal dengan strip merah-putih rata. Jalan besar memisahkan plant dan gedung; finfan dipindahkan ke utilitas. Pertigaan diberi garis berhenti dan STOP. Tanker Pertamina memakai loading arm bersendi untuk persiapan animasi. Karakter Pertamina memakai earmuff; pickup hitam dan putih dari aset pengguna.

## Bandara

Pesawat, refueller, apron, marka stand, jalur servis, serta terminal berkaca dan kanopi. Empat tanki putih T-401 sampai T-404 tersusun 2x2 dekat loading arm penerimaan. Tanki memiliki tangga melingkar, rail kuning, pijakan hitam, dan label mengikuti shell. Depot memiliki containment, manifold inlet-outlet, pompa transfer, dan titik pengisian refueller.

## Audit terakhir

**Belum final untuk render close-up fotorealistis.**

Perbaikan tersimpan:

- Sinkronisasi 15 flow-guide dengan pipa aktif serta penambahan guide pompa/depot.
- Pipa melintang jalan dermaga dialihkan ke bawah jalan.
- Loading arm bandara digeser ke arah air.
- Link texture barrel hilang dilepas dari shader terdampak, diganti nilai PBR.
- Scan tidak menemukan transform non-finite atau mesh scene tanpa vertex.

Masih terbuka:

- Refinement close-up pesawat, refueller, dan karakter.
- Fuel Gas/CDU II masih terminal eksternal; jaringan lengkap belum dimodelkan.
- Collision menyeluruh dan sweep seluruh frame animasi belum dilakukan.
- Optimasi vegetasi dan review framing kamera final.
- Audit ini bukan validasi engineering atau kepatuhan operasional.

## File dan batas arsip

File kerja utama: `saf_plant_polished.blend`. Backup perubahan besar tersedia lokal. File Blender, gambar referensi, slide, dan transkrip lengkap belum diunggah.

## Auto-update

Belum aktif. Diperlukan sumber ekspor chat terverifikasi dan autentikasi Git pada Mac. Rencana: ekspor pesan pengguna/asisten ke Markdown, deteksi perubahan, commit, lalu push hanya file arsip. Jangan menyertakan cookie, token, credential, atau percakapan lain.
