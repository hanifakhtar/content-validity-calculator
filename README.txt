CONTENT VALIDITY CALCULATOR — GITHUB PAGES (VERSI SATU FILE)
===============================================================

Cara pasang:
1. Buat repository GitHub, misalnya: content-validity-calculator
2. Upload file index.html dari ZIP ini ke repository tersebut (di root, bukan dalam subfolder).
3. Buka Settings > Pages > Build and deployment.
4. Pilih Deploy from a branch > main > /(root) > Save.
5. Buka URL Pages: https://USERNAME.github.io/content-validity-calculator/

App ini benar-benar HTML + CSS + JavaScript, seluruhnya di dalam satu file.
Tidak memerlukan R, server Shiny, GitHub Actions, API, API key, build, atau CDN.
Template Excel bisa diunduh dari app, dan hasil bisa diekspor sebagai .xlsx / CSV.

Fitur: input manual atau file Excel .xlsx/CSV/TSV, I-CVI, S-CVI/Ave,
S-CVI/UA, modified kappa, Aiken's V, confidence interval, right-tail
p-value, pemeriksaan kesalahan, interpretasi, laporan bahasa ID/EN,
dan ekspor Excel 8 sheet.

Data diproses lokal di browser, bukan diunggah ke server. .xls lama tidak
didukung; konversi ke .xlsx terlebih dahulu.

Catatan: tidak ada cutoff Aiken's V universal pada aplikasi.
