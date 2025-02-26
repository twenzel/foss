## About Duende.IdentityModel.OidcClient
Duende.IdentityModel.OidcClient is an OpenID Connect (OIDC) client library for native
applications. It provides
- Types that describe OIDC requests and responses
- Low level methods to construct protocol state and handle responses
- Higher level methods for 
   - Logging in
   - Logging out
   - Retrieving userinfo
   - Refreshing tokens

## Samples
Duende.IdentityModel.OidcClient targets .NET Standard, making it suitable for .NET and
.NET Framework. It can be used to build OIDC native clients with a variety of .NET UI
tools. The
[samples](https://github.com/DuendeSoftware/foss/tree/main/identity-model-oidc-client/samples)
directory shows how to use it in 
- .NET MAUI
- WPF with the system browser
- WPF with an embedded browser
- WinForms with an embedded browser
- Cross Platform Console Applications (relies on kestrel for processing the callback)
- Windows Console Applications (relies on an HttpListener - a wrapper around the windows HTTP.sys driver)
- Windows Console Applications using custom uri schemes

## Documentation 

More documentation is available
[here](https://docs.duendesoftware.com/foss/identitymodel.oidcclient/).

## Standards and Certification
Duende.IdentityModel.OidcClient is a [certified](http://openid.net/certification/) OpenID
Connect relying party implementation, and implements  
[RFC 8252](https://tools.ietf.org/html/rfc8252/), "OAuth 2.0 for native Applications".

![openid_certified](https://cloud.githubusercontent.com/assets/1454075/7611268/4d19de32-f97b-11e4-895b-31b2455a7ca6.png)

## Related Packages

- Library for claims-based identity, OAuth 2.0, and OpenID Connect:
  [Duende.IdentityModel](https://www.nuget.org/packages/Duende.IdentityModel)
- Extensions to this library, including DPoP support:
  [Duende.IdentityModel.OidcClient.Extensions](https://www.nuget.org/packages/Duende.IdentityModel.OidcClient.Extensions)

## Feedback

Duende.IdentityModel.OidcClient is released as open source under the Apache 2.0
[license](https://github.com/DuendeSoftware/foss/blob/main/LICENSE). Bug reports and
contributions are welcome at [the GitHub
repository](https://github.com/DuendeSoftware/foss/issues).
