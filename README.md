# cloudflare-ddns
Cloudflare DYNDNS update script

Works with Windows - macOS - Linux

I use it along with crontab to run every 5 minutes.

Do a ```crontab -e``` and insert the following line of code (also replace path!!):

```*/5 * * * * python /path-to/cloudflare-ddns.py```

Ctrl+wq and enter , and it's done!
