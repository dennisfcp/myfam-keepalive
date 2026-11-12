# myfam-keepalive

Pings the MyFam API `/health` endpoint every 14 minutes between 06:00 and 22:59 UTC so the free
Render instance does not go to sleep. The only file that matters is
`.github/workflows/keepalive.yml`. Run it by hand from the Actions tab (`workflow_dispatch`).

No secrets are used.
