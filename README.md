# Backups criptografados do ChatNOC ERP

Gerados por /opt/ops/backup/erp-backup.sh na VPS do ERP. Ultimo: chatnoc-erp-20261031T030046-0300.tar.age

Restaurar: `age -d -i chave-privada.txt arquivo.tar.age | tar -xf -`
e depois `pg_restore -d chatnoc_erp --clean --if-exists chatnoc_erp.dump`.
