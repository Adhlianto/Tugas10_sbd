## Nama   : Agung Adlhianto
## NIM    : 311910570
## Kelas  : TI.19.B.2

# Membuat Backup dan Recovery

### 1. Membuat Backup dan Recovery Data
![backup and recovery](https://user-images.githubusercontent.com/56548203/125173747-01e0b580-e1eb-11eb-8b2a-ba0a6fee0563.JPG)
### 2. Membuat Back Up di MYSQLDUMP
![mysqldump](https://user-images.githubusercontent.com/56548203/125173777-2ccb0980-e1eb-11eb-902a-eaa613ec8858.JPG)

# SCRIPT CRONJOB BACKUP OTOMATIS SELAMA 12 JAM
0 0 * * 7 mysqldump -u root -p78545 agungadlhianto_311910570 > agungadlhianto_311910570_backup.sql
