WiFi_Check

Purpose:
Script checks to see if WiFi has a network IP and if not
restart WiFi

Uses a lock file which prevents the script from running more
than one at a time.  If lockfile is old, it removes it

```bash
$ chmod +x WiFi_Check
$ sudo vim /etc/crontab
*/1 * * * * root /absolute/path/to/WiFi_Check
```
