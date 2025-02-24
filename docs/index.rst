Overview
========
IdentityModel is a family of libraries for building OAuth 2.0 and OpenID Connect clients.

IdentityModel
-------------
Base library for OIDC and OAuth 2.0 related protocol operations and constants and other misc helpers (.NET Standard 2.0 / .NET Framework >4.6.1).

* github https://github.com/IdentityModel/IdentityModel
* nuget https://www.nuget.org/packages/IdentityModel/
* CI builds https://github.com/orgs/IdentityModel/packages

IdentityModel.AspNetCore
------------------------
ASP.NET Core specific helper library for token management.

* github https://github.com/IdentityModel/IdentityModel.AspNetCore
* nuget https://www.nuget.org/packages/IdentityModel.AspNetCore/
* CI builds https://github.com/orgs/IdentityModel/packages

IdentityModel.AspNetCore.OAuthIntrospection
-------------------------------------------
OAuth 2.0 token introspection authentication handler for ASP.NET Core.

* github https://github.com/IdentityModel/IdentityModel.AspNetCore.OAuthIntrospection
* nuget https://www.nuget.org/packages/IdentityModel.AspNetCore.OAuthIntrospection/
* CI builds https://github.com/orgs/IdentityModel/packages

IdentityModel.OidcClient
------------------------
.NET based implementation of the **OAuth 2.0 for native apps** BCP. Certified by the OpenID Foundation.

* github https://github.com/IdentityModel/IdentityModel.OidcClient
* nuget https://www.nuget.org/packages/IdentityModel.OidClient
* CI builds https://github.com/orgs/IdentityModel/packages

oidc-client.js
--------------
JavaScript based implementation of the **OAuth 2.0 for browser-based applications** BCP. Certified by the OpenID Foundation

* github https://github.com/IdentityModel/oidc-client-js
* npm https://www.npmjs.com/package/oidc-client


.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: IdentityModel

   client/overview
   client/discovery
   client/token
   client/introspection
   client/revocation
   client/userinfo
   client/dynamic_registration
   client/device_authorize

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: IdentityModel - Misc Helpers

   misc/constants
   misc/request_url
   misc/x509store
   misc/base64
   misc/epoch_time
   misc/time_constant_comparison

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Building mobile/native Clients

   native/overview
   native/manual
   native/automatic
   native/logging
   native/samples

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: Building JavaScript Clients

   js/overview
