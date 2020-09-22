# SSL Verifier
SSL Verifier for Node.js &amp; Let's Encrypt &amp; Certbot

> From [ITNEXT](https://itnext.io/node-express-letsencrypt-generate-a-free-ssl-certificate-and-run-an-https-server-in-5-minutes-a730fbe528ca)

## Index
1. Run `sudo certbot certonly --manual`, and then `npm i express -s`
2. Create directory named `acme-challenge` inside `.well-known` folder
3. Create file in `./.well-known/acme-challenge/a-string`, and insert `a-challenge` in the file.
4. [Run Initial Server and create directory](init.js)
5. You're now done!
