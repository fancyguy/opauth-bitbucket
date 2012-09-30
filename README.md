Opauth-Bitbucket
=============
[Opauth][1] strategy for Bitbucket authentication.

Implemented based on https://confluence.atlassian.com/display/BITBUCKET/oauth+Endpoint using OAuth.

Opauth is a multi-provider authentication framework for PHP.

Getting started
----------------
1. Install Opauth-Google:
   ```bash
   cd path_to_opauth/Strategy
   git clone git://github.com/fancyguy/opauth-bitbucket.git Bitbucket
   ```

2. Create a Bitbucket integrated application under account then Integrated applications
   - Click on create consumer and enter your application name.
   - Description and URL are optional.
   
3. Configure Opauth-Bitbucket strategy.

4. Direct user to `http://path_to_opauth/bitbucket` to authenticate


Strategy configuration
----------------------

Required parameters:

```php
<?php
'Bitbucket' => array(
	'key' => 'YOUR CONSUMER KEY',
	'secret' => 'YOUR CONSUMER SECRET'
)
```

License
---------
Opauth-Bitbucket is MIT Licensed  
Copyright © 2012 FancyGuy Technologies (http://www.fancyguy.com)

[1]: https://github.com/uzyn/opauth