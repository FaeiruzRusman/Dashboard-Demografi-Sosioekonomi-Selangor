# Dashboard Demografi & Sosioekonomi Negeri Selangor (SUO)

Dashboard statik GitHub Pages dengan **data rasmi DOSM**, tanpa data simulasi.

## Dataset tempatan
- `data/population_district_selangor_part1.csv` hingga `part3.csv`: 25,137 rekod penduduk daerah, 2020–2026 (unit asal: ribu orang).
- `data/population_state_selangor_part1.csv` dan `part2.csv`: 17,814 rekod penduduk negeri, 1970–2026 (rujukan tambahan).
- `data/hh_income_district_selangor.csv`: 27 rekod pendapatan isi rumah, 2019, 2022, 2024.
- `data/hh_poverty_district_selangor.csv`: 27 rekod kemiskinan isi rumah, 2019, 2022, 2024.

Fail populasi dipecahkan untuk pengurusan muat naik; hanya bahagian pertama mengandungi baris header. Kod `index.html` mencantumkan rekod sebelum memaparkan dashboard. Data `population_state` disimpan sebagai rujukan, tidak dicampur secara automatik ke dalam jumlah daerah.

Sumber asal: [OpenDOSM](https://open.dosm.gov.my/) / [DOSM](https://www.dosm.gov.my/). Semak penerbitan rasmi sebelum mentafsir perbandingan tahun berlainan. Sebarang ralat memuatkan fail akan dipaparkan, bukan digantikan dengan angka demo.

## Hosting
GitHub Pages: `main` → `/(root)`. Dataset dihidangkan dari folder `data/` repository yang sama.
