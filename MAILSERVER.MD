Important steps :
- SPF
- DKIM >= 2048 bits
- DMARC
- ARC
- IP/EHLO/REVERSE PTR
- MX records
- A/AAAA records
- Valid email headers
- Valid email payload
- Emails must respect RFC5322
- Not blacklisted in common RBLs
### Rejoin provider's junk email program :
- https://postmaster.google.com/
- https://postmaster.live.com/snds/
- (Fork this repo if you want to add new postmaster service like google or yahoo)

### Rejoin whitelisting services :
- https://www.dnswl.org/
- http://www.spamhauswhitelist.com/
- (Fork this repo if you want to add new postmaster service like google or yahoo)

- Contact provider feedback-loop
- Be patient and build up a good sender reputation

Special Thanks to
- [@hardware](https://github.com/hardware)

Reference|Source:
- https://github.com/hardware/mailserver/issues/210
