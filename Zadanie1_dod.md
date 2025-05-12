# Zadanie 1 – Serwer + Docker

## Opis projektu

Ten projekt zawiera prosty serwer [wstaw język/program np. Python/Node.js], który odpowiada na żądania HTTP. Całość została opakowana w obraz Dockera, co pozwala na łatwe uruchomienie w dowolnym środowisku obsługującym Docker.

## Zawartość repozytorium

- `zadanie1_dod.md` – ten plik, opisujący projekt.
- `Dockerfile` – instrukcja budowania obrazu Dockera.
- `[nazwa_pliku_źródłowego]` – plik źródłowy z kodem serwera.
- (opcjonalnie) `requirements.txt` / `package.json` – zależności projektu.
- (opcjonalnie) inne pliki konfiguracyjne, jeśli są potrzebne.

## Jak uruchomić

### 1. Budowa obrazu Dockera

```bash
docker buildx create --name multiplatformBuilder --driver docker-container –bootstrap
