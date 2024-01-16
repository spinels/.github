# Spinels

Resurrecting old gems.

## TODO

`overman`

* https://github.com/spinels/overman/issues/2 (still not all processes are killed)

`rerun`

* https://rubygems.org/gems/rerun
* https://github.com/alexch/rerun
  * https://github.com/spinels/rerun/issues/1
  * https://github.com/alexch/rerun/issues/145 (no recent release with some fixes)

`rack-timeout`

* https://rubygems.org/gems/rack-timeout
* https://github.com/zombocom/rack-timeout
  * many good open PRs, and some closed ones:
  * https://github.com/zombocom/rack-timeout/pull/201
  * https://github.com/zombocom/rack-timeout/pull/165

`sprockets-helpers`

* https://rubygems.org/gems/sprockets-helpers
* https://github.com/petebrowne/sprockets-helpers

`sinatra-asset-pipeline`

* https://rubygems.org/gems/sinatra-asset-pipeline
* https://github.com/kalasjocke/sinatra-asset-pipeline

`rack-flash3`

Last release was `1.0.5 - September 03, 2013`

* https://rubygems.org/gems/rack-flash3
* https://github.com/treeder/rack-flash

## DONE

`foreman` → [`overman`](https://github.com/spinels/overman)

* Merged `Run processes in new process groups, kill process group instead of process` https://github.com/ddollar/foreman/pull/780

`rack-ssl-enforcer` → [`spinels-rack-ssl-enforcer`](https://github.com/spinels/rack-ssl-enforcer)

* Modern CI
* Merged `Make middleware thread-safe` PR: https://github.com/tobmatth/rack-ssl-enforcer/pull/105

`racksh` → [`spinels-racksh`](https://github.com/spinels/racksh)

* Merged `use File.exist? because Ruby 3.2 does not have File.exists?` https://github.com/sickill/racksh/pull/15
