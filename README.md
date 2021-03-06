# A Laravel package to manage your email lists, tags and subscribers for a variety of marketing tools

## Features
- View all lists and list subscribers
- View all subscribers

Planned features:
- Create and edit lists
- Create and edit subscribers
- Create, edit and view tags

Currently supported email tools:
- ActiveCampaign
- GetResponse
- MailChimp

Planned:
- AWeber
- ConstantContact
- ConvertKit
- Drip

Feel free to request any other providers 

## Installation

### Requirements
- Laravel

First install the package through Composer:
```
composer require r64/laravel-email-marketing
```

Publish the config: 
```
php artisan vendor:publish --tag=email-marketing
```

Then in your .env add:
```
EMAIL_MARKETING_DRIVER= 
```
Valid drivers are activecampaign, getresponse and mailchimp

Add the keys for your tool of choice:

ActiveCampaign
```
ACTIVECAMPAIGN_API_KEY=
ACTIVECAMPAIGN_URL=
```

GetResponse
```
GETRESPONSE_API_KEY=
```

MailChimp
```
MAILCHIMP_API_KEY=
```
