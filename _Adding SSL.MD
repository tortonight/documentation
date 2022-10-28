There are many ways to add SSL to your site. A simple solution is to use Cert bot from Let’s Encrypt. Cert bot will automatically install the certificates for you and keep your SSL certifications up to date!

```bash
sudo apt update
#install certbot for nginx
sudo apt install -y certbot
sudo apt install -y python3-certbot-nginx
#install certificates
sudo certbot --nginx -d yourdomain.com
```
