# chef-repo

```
knife solo init .
knife solo prepare host
knife solo cook host nodes/host.json

berks install

chef generate repo chef-repo
chef generate cookbook site-cookbooks/hoge
chef generate template site-cookbooks/hoge hoge_app



bundle init

Gemfile
gem 'berkshelf'
gem 'knife-solo'
gem 'knife-solo_data_bag'
```

Berksfile

```
source "https://supermarket.chef.io"
cookbook 'apache2', '~> 5.0.1'

```
