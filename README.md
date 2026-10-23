# Bludit Docker Setup

Ein leichtgewichtiges Docker-Setup für das Bludit CMS auf Basis von Nginx und PHP-FPM.

## Schnellstart

1. Repository klonen:
   ```bash
   git clone [https://github.com/DEIN-USERNAME/DEIN-REPO.git](https://github.com/DEIN-USERNAME/DEIN-REPO.git)
   cd DEIN-REPO
   ```
2. Konfigurationsdatei erstellen:
   ```bash
   cp .env.example .env
   ```  
3. Bludit herunterladen und im Ordner web/ entpacken (falls noch nicht geschehen).
4. Container starten:
   ```bash
   docker compose up -d --build
   ```
5. Aufrufen unter http://localhost:8080 (oder dem in .env definierten Port).
