## backup web - crontab container (jail) backup.
---

```bash
root@manunggul [~/] #: bastille console backup
root@manunggul [~/] #: crontab -e
0 * /3 * * * ~/bin/bacuk_web
root@manunggul [~/] #: Ctrl+d
```

#### "Leo"

> Esse script roda somente no container (jail). Se tentar usar fora ele não vai
> funcionar.

---
