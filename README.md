centos6-ruby187
===============

CentOS minimal + Ruby 1.8.7 + RubyGems 1.3.7 with epel, rpmforge, remi repositories

## How to setup

    curl https://raw.github.com/ir3/centos6-ruby187/master/setup.sh | sudo sh -

## ruby

    # ruby=ruby-1.8.7-p374;/opt/${ruby}/bin/ruby -v
    ruby 1.8.7 (2013-06-27 patchlevel 374) [x86_64-linux]
    # echo "puts 'hello ruby'" | /opt/${ruby}/bin/ruby
    hello ruby
