# Miidia

Distribuição e auto-atualização do aplicativo Miidia.

- `version.json` — manifesto da versão mais recente (`versionCode`, `versionName`, `apkUrl`, `notes`).
- `miidia.apk` — pacote de instalação mais recente.

O app consulta o `version.json`, compara com a versão instalada e, havendo uma mais nova, baixa e instala o `miidia.apk`.
