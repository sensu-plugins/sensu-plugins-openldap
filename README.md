## Sensu-Plugins-openldap

[![Build Status](https://travis-ci.org/sensu-plugins/sensu-plugins-openldap.svg?branch=master)](https://travis-ci.org/sensu-plugins/sensu-plugins-openldap)
[![Gem Version](https://badge.fury.io/rb/sensu-plugins-openldap.svg)](http://badge.fury.io/rb/sensu-plugins-openldap)
[![Code Climate](https://codeclimate.com/github/sensu-plugins/sensu-plugins-openldap/badges/gpa.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-openldap)
[![Test Coverage](https://codeclimate.com/github/sensu-plugins/sensu-plugins-openldap/badges/coverage.svg)](https://codeclimate.com/github/sensu-plugins/sensu-plugins-openldap)
[![Dependency Status](https://gemnasium.com/sensu-plugins/sensu-plugins-openldap.svg)](https://gemnasium.com/sensu-plugins/sensu-plugins-openldap)

## Functionality

## Files
 * bin/check-syncrepl
 * bin/metrics-ldap

## Usage

## Installation

Add the public key (if you haven’t already) as a trusted certificate

```
gem cert --add <(curl -Ls https://raw.githubusercontent.com/sensu-plugins/sensu-plugins.github.io/master/certs/sensu-plugins.pem)
gem install sensu-plugins-openldap -P MediumSecurity
```

You can also download the key from /certs/ within each repository.

#### Rubygems

`gem install sensu-plugins-openldap`

#### Bundler

Add *sensu-plugins-disk-checks* to your Gemfile and run `bundle install` or `bundle update`

#### Chef

Using the Sensu **sensu_gem** LWRP
```
sensu_gem 'sensu-plugins-openldap' do
  options('--prerelease')
  version '0.0.1'
end
```

Using the Chef **gem_package** resource
```
gem_package 'sensu-plugins-openldap' do
  options('--prerelease')
  version '0.0.1'
end
```

## Notes
