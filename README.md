# cronjobs

Cronjob, Linux/Unix sistemlerinde belirli zamanlarda otomatik çalışan görevlerdir.
- Günlük yedek alma
- Rapor hazırlama
- Sunucu scriptlerini otomatik çalıştırma gibi görevleri yapar

cron sekmesini görüntüler (görevler)

  ```bash
  crontab -l
  ```
crontab sekmesi açılır ve editör seçilir, nano en mantıklısı , crontab düzenleme yapılır

  ```bash
crontab -e
```

# örnek cronjobslar
```
0 9 * * * /home/user/backup.sh  //Her gün saat 12:00’de backup.sh çalışır
```
