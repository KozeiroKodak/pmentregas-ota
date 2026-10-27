# PMEntregas OTA

Repositório público exclusivo para distribuição dos pacotes OTA do aplicativo PMEntregas.

- Fonte privada: https://github.com/KozeiroKodak/pmentregas
- OTA público: https://github.com/KozeiroKodak/pmentregas-ota
- Clone SSH: `git clone git@github.com:KozeiroKodak/pmentregas-ota.git`

## Situação

Pré-configuração concluída. **Nenhuma atualização foi publicada**.
O `manifest.json` com versão `0.0.0`, pacote e SHA nulos indica ausência de release.

## Publicação

A publicação será iniciada **manualmente**, por workflow do repositório privado PMEntregas, após a configuração do segredo `OTA_REPO_TOKEN` e validação da primeira versão.
O pacote é criado exclusivamente dos arquivos web canônicos na raiz da `main` privada, sem `www/`, `android/`, segredos, testes ou scripts de desenvolvimento.

Formato futuro de release: `ota-web-X.Y.Z`, com arquivo `pmentregas-web-X.Y.Z.zip`, manifesto público e SHA-256.

**Nunca faça commit de chaves, tokens ou segredos neste repositório público.**
