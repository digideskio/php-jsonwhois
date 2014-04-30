# php-jsonwhois

A PHP Library for the jsonwhois API

## Requirements

PHP version >= 5.3.0.

## Installing

 ``` json
    {
        "require": {
            "mfasanya/php-jsonwhois": "dev-master"
        }
    }
 ```
## Configuring

 ``` php
    use JsonWhois\JsonWhois;

    $API = new JsonWhois();

    $API->apiKey("API KEY");
 ```
# Usage

  ``` php
    $whois =  $API->whois('bloom.com');
    $screenshot =  $API->screenshot('bloom.com');
   ```

And thats it!

## License

MIT