# Zadanie 1 – Serwer + Docker

## Opis projektu

Zadanie 1 część nieobowwiązkowa. Zbudowanie kontenera z kodem z cześci obowiązkowej na dwie platformy sprzętowe. 

## Kroki

### 1. Budowa obrazu Dockera

```bash
docker buildx create --name multiplatformBuilder --driver docker-container –bootstrap
