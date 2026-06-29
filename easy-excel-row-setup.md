# Cara Paling Mudah Non-Premium: Copy Excel Row

Cara ini tidak pakai Power Automate, tidak pakai Google Apps Script, dan tidak perlu Microsoft Client ID.

Alur kerja:

```text
brief.html -> Copy Excel Row -> buka Excel -> Ctrl+V
```

## 1. Siapkan Excel Table

Buka workbook Excel SharePoint.

Buat header kolom:

```text
Created At
Size
KV
Winner Count
Logo
Footer
MY Insert
MY Wording
MY Prize
PH Insert
PH Wording
PH Prize
TH Insert
TH Wording
TH Prize
Full Brief
```

Blok header, lalu pilih:

```text
Insert > Table
```

## 2. Cara Pakai Setiap Campaign

1. Buka `brief.html`.
2. Isi campaign seperti biasa.
3. Klik `Copy Brief` untuk brief design.
4. Klik `Copy Excel Row`.
5. Buka Excel SharePoint.
6. Klik cell pertama di baris kosong table.
7. Tekan:

```text
Ctrl + V
```

Satu baris database akan langsung terisi semua kolom.

## Kenapa Ini Paling Simple

- Tidak perlu download CSV.
- Tidak perlu import file.
- Tidak perlu Power Automate Premium.
- Tidak perlu App Registration.
- Tetap pakai Excel SharePoint sebagai database.

