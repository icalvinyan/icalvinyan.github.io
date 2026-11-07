# icalvinyan.github.io

Hosts the public key for the Tesla Fleet API app used by Home Assistant:
https://icalvinyan.github.io/.well-known/appspecific/com.tesla.3p.public-key.pem

Only the public key belongs here. The private key stays on Home Assistant
(`/config/tesla_fleet.key`) and must never be committed.

`.nojekyll` stops GitHub Pages from hiding the `.well-known` folder.
