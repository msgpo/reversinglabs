# Polarity ReversingLabs Integration

Polarity's ReversingLabs integration gives users access to automated MD5, SHA1, SHA256 lookups within ReversingLabs.  

> This integration can also support lookups on IPv4, email, url, and domains.  Note that these lookups are disabled by default as they are produce a lot of results.  You can enable these entity types by turning the on in your /config/config.js file under the `entityTypes` property.  

ReversingLabs is a world leader in file reputation and analysis with over 8 billion files analyzed to date. To get more information on ReversingLabs, please visit https://www.reversinglabs.com

![bba82046-f872-4fad-b66f-7330ec7909bc](https://user-images.githubusercontent.com/306319/53984862-33f81f00-40e8-11e9-828a-fa47d44268e6.GIF)

## ReversingLabs Integration Options

### ReversingLabs' TitaniumCloud Server URL

TitaniumCloud Server which should include the schema (i.e., https://) and port if required

### Username

ReversingLabs' TitaniumCloud API Username

### Password

ReversingLabs' TitaniumCloud password

### Ignore Known Samples

If checked, the integration will only return results for samples that are marked as "Malicious" or "Suspicious". Samples marked as "Known" will be ignored.

### View data in A1000

If checked, the integration will create a link that allows users to view information in their A1000 system

### ReversingLabs' A1000 Server URL

A1000 Server URL which should include the schema (i.e., https://) and port if required

### Associated hashes for non-hash entity types

Number of associated hashes to show in the details when a hit is received for a non-hash entity type.  

> For this option to have an effect, additional entity types (IPv4, url, domain, email) must be enabled in your config/config.js file
## Installation Instructions

Installation instructions for integrations are provided on the [PolarityIO GitHub Page](https://polarityio.github.io/).

## Polarity

Polarity is a memory-augmentation platform that improves and accelerates analyst decision making.  For more information about the Polarity platform please see:

https://polarity.io/
