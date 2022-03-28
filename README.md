# Spinels

Resurrecting old gems.

## TODO

### `rack-flash3`

Last release was `1.0.5 - September 03, 2013`

* https://rubygems.org/gems/rack-flash3
* https://github.com/treeder/rack-flash

### Sinatra

https://rubygems.org/gems/sinatra - No release since 2.1.0 (Sep 04, 2020)

Fixes waiting for a release: 

* **Related to breaking changes in v2.1.0** 
  * About `content_type`: https://github.com/sinatra/sinatra/pull/1649
  * About helpers: https://github.com/sinatra/sinatra/pull/1662
* **Ruby 3 compatibility** 
  * `Delegator` fix: https://github.com/sinatra/sinatra/pull/1684
  * `use` with keyword arguments: https://github.com/sinatra/sinatra/pull/1701

### Rack::Protection

https://rubygems.org/gems/rack-protection - No release since 2.1.0 (Sep 04, 2020)

* Be able to enable `EscapedParams` from Sinatra https://github.com/sinatra/sinatra/pull/1632

### Mustermann

https://rubygems.org/gems/mustermann - No release since 1.1.1 (Jan 03, 2020)

* `Support Ruby 3.0` https://github.com/sinatra/mustermann/issues/114

## DONE

### Rack::SslEnforcer

* Modern CI
* Merged `Make middleware thread-safe` PR: https://github.com/tobmatth/rack-ssl-enforcer/pull/105
