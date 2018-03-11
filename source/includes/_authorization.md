# Authorization

Authorization for the fileee APIs in general follows the [OAuth 2.0](https://tools.ietf.org/html/rfc6749) standard. When working with end user accounts, it specifically uses the [Authorization Code Grant](https://tools.ietf.org/html/rfc6749#section-4.1) type.

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Authorization: Bearer thisIsMyAccessToken"
```

> Make sure to replace `thisIsMyAccessToken` with the actual access token you were issued.
