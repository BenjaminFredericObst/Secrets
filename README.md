# Projekt-Dokumentation

## GitHub Actions Workflow mit Secrets

Dieses Repository enthält eine GitHub Actions Pipeline, die ein Secret (`API_KEY`) verwendet.

### Setup
1. Secret in GitHub hinzufügen:  
   - `Settings` → `Secrets and variables` → `Actions`  
   - `API_KEY` mit einem Dummy-Wert anlegen  
2. Datei `.github/workflows/secret-test.yml` erstellt.
3. Das Secret wird als Umgebungsvariable im Workflow genutzt.

### Workflow-Übersicht
- Nutzt `API_KEY` für API-Zugriffe.
- Überprüft, ob das Secret gesetzt ist.
- Simuliert eine API-Anfrage mit dem Secret.
