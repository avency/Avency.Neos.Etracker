# Avency.Neos.Etracker

> Adds the etracker code in the html header.

## Authors & Sponsors
Michael Gerdemann - michael.gerdemann@avency.de<br>
Enes Erk - enes.erk@avency.de

The development and the public-releases of this package is generously sponsored by our employer https://www.avency.de.

## Installation

```
composer require avency/neos-etracker
```

## Configuration

### Key and siteArea

Configure the key and, if necessary, the SiteArea string in Settings.yaml:

```
Avency:
  Neos:
    Etracker:
      key: ''
      siteArea: ''
```

Or add the mixin to your root page:

```
  superTypes:
    'Avency.Neos.Etracker:Mixin.Etracker': true
```

### Disable block cookies by default

```
Avency:
  Neos:
    Etracker:
      blockCookies: false
```

[Documentation (German)](https://www.etracker.com/docs/integration-setup/einstellungen-accounts/etracker-cookies/etracker-cookies-aktivieren/#anleitung)

### Set cookie lifetime

```
Avency:
  Neos:
    Etracker:
      cookieLifeTime: 24 # Amount of Months
```

[Documentation (German)](https://www.etracker.com/docs/integration-setup/einstellungen-accounts/etracker-cookies/laufzeit-von-etracker-cookies-selbst-bestimmen/)

## License

The MIT License (MIT). Please see [License File](./LICENSE.md) for more information.
