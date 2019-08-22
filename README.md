# Mailchimp Provider for OAuth 2.0 Client

## Installation

To install, use composer:

```
composer require chadhutchins/oauth2-mailchimp
```

## Usage

Usage is the same as The League's OAuth client, using `\Chadhutchins\OAuth2\Client\Provider\Mailchimp` as the provider.

### Authorization Code Flow

```php
$provider = new \Chadhutchins\OAuth2\Client\Provider\Mailchimp([
    'clientId'          => '{mailchimp-client-id}',
    'clientSecret'      => '{mailchimp-client-secret}',
    'redirectUri'       => 'https://example.com/callback-url',
]);
```
For further usage of this package please refer to the [core package documentation on "Authorization Code Grant"](https://github.com/thephpleague/oauth2-client#usage).

## Credits

- [Chad Hutchins](https://github.com/chadhutchins)
- [Steven Maguire](https://github.com/stevenmaguire) - Thanks to Steven's other third-party providers, I learned how to do this.
- [All Contributors](https://github.com/chadhutchins/oauth2-mailchimp/contributors)


## License

The MIT License (MIT). Please see [License File](https://github.com/chadhutchins/oauth2-mailchimp/blob/master/LICENSE) for more information.
