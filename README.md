# README
```
Ruby        2.5.1p57
Bundler     1.17.1
Rails       5.2.2
Mysql       Ver 14.14 Distrib 5.6.35
```

```
This app allows users to:
- Register / login
- Upload images (edit/delete)
```

```
What was used:
- Devise
- 
- Carrier wave - to upload images
- S3 for storage (and fog)
- mini_magick for image conversion
- Stripe for payments (The user needs to select a plan at the registration step)
- Sendgrid for Emails
- Bootstrapt + Twitter Bootstrap for Front End
```

Prod Url -> https://joao-photo-app.herokuapp.com/