# traefik-sample v2

This is a simple traefik setup sample.

## List of containers installed:

- **Traefik v3.3.4** - reverse proxy service
- **Nginx-alpine** - for return error page
- **Cloudflared** - for tunneling service
- **TinyAuth** - for Oauth

## Additionally, these are required:

- Google **OAuth API ID and Secret**
- CloudFlare **ID and API Token, Cloudflare Origin Cert**
- Linux Environments(for use curl, call cloudflare api)
- and your **Personal Domain**

please refer to the **docker-compose.yml** file and the **sample.env** file.

You must change the file name **"sample.env"** to **".env"**.

**plz.delete file** is a dummy file added to create a folder. Please delete it.