# Manga deposu

`index.pb` birleştirme düzeni (Anime İzle için). Yayınlanan adres:

`https://raw.githubusercontent.com/TarikCinetci/TarikCinetci.github.io/repo/index.pb`

- `sources.json`: birleştirilecek depolar. Değiştirip push edince otomatik yeniden üretilir.
- `merge_repos.py`: birleştirici (yalnızca Python standart kütüphanesi). `test_merge.py` testleri.
- Otomasyon: `.github/workflows/manga-repo.yml` (her gün 03:17 UTC ve elle çalıştırılabilir). Sonuç `repo` dalına yazılır; site dalına (`main`) dokunmaz.
