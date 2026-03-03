# Yuumei VTuber no Ani Dakedo, Nazeka Ore ga Yuumei ni Natteita

> Aku punya adik tiri bernama Isuzu. Dia adalah VTuber super populer dengan lebih dari 1 juta subscriber, 'Isuzu Wine'.Suatu hari, dia lupa mematikan siaran, dan percakapan aslinya denganku tanpa sengaja tersebar ke seluruh dunia!Potongan video insiden siaran itu dengan cepat menyebar, dan dalam semalam, aku mendadak jadi selebriti internet...!?Semakin banyak insiden, semakin melonjak popularitasnya!!Bersama adik tiri yang manja dan terlalu cantik, serta senior VTuber yang imut, aku mulai meniti karir di dunia streaming!Kisah komedi romantis tentang VTuber yang mendadak naik daun!

---

## Info

| | |
|---|---|
| Judul | Yuumei VTuber no Ani Dakedo, Nazeka Ore ga Yuumei ni Natteita |
| Judul Alternatif | 有名VTuberの兄だけど、何故か俺が有名になっていた |
| Author | Ibarakino |
| Artist | Shio Takoyaki |
| Tipe | Manga (Hitam Putih) |
| Status | Ongoing |
| Genre | Shounen · Comedy · Romance · School Life · Slice of Life |
| Chapter | 29 chapter (1 locked) |

## Link

- [MangaDex](https://mangadex.org/title/9aebe60e-777f-4a58-a3bf-143c3096b94f/yuumei-vtuber-no-ani-dakedo-nazeka-ore-ga-yuumei-ni-natteita)
- [Raw](https://www.manga-up.com/titles/1289)

---

## Struktur

```
YuumeiVTuber/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)