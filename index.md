
# CENTRALA-BACKUP

Soukromý nástroj pro automatické zálohování
databáze CENTRÁLA.

## Jak aplikace funguje

Aplikace používá GitHub Actions, Supabase,
šifrování age a Google Drive.

Vytváří šifrované záložní soubory a ukládá
je na Google Drive vlastníka.

Přístup ke Google Drive je omezen na soubory
používané touto aplikací.

Obnovení databáze se provádí pouze
se souhlasem vlastníka.

## Ochrana osobních údajů

[Zásady ochrany soukromí](privacy.md)
