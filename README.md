# Neos CMS Cookie Consent Banner

A Neos CMS plugin to integrate the Cookie Banner from cookieconsent.insites.com

## Installation

The NeosRulez.CookieConsent package is listed on packagist (https://packagist.org/packages/neosrulez/cookieconsent) - therefore you don't have to include the package in your "repositories" entry any more.

Just add the following line to your require section:

```
"neosrulez/cookieconsent": "*"
```

And the run this command to fetch the plugin:

```
composer update
```

## Settings.yaml

In your site package Settings.yaml you can make your adjustments.

```
NeosRulez:
  CookieConsent:
    position: 'default'
    #position: 'top'
    #position: 'bottom-left'
    #position: 'bottom-right'
    layout: 'default'
    #layout: 'classic'
    #layout: 'edgeless'
    #layout: 'wire'
    colorBanner: '#000000'
    colorBannerText: '#FFFFFF'
    colorButton: '#999999'
    colorButtonText: '#FFFFFF'
    learnMoreLink: '/privacy.html'
    messageText: 'This website uses cookies to ensure you get the best experience on our website.'
    dismissButtonText: 'Got it!'
    policyLinkText: 'Learn more'
```

## Author

* E-Mail: mail@patriceckhart.com 
* URL: http://www.patriceckhart.com 