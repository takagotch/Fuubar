### Fuubar
---
https://github.com/thekompanee/fuubar

```
gem install fuubar
gem 'fuubar'
rspec --format Fuubar --color spec
--format Fuubar
--color

gem cert -add <(curl -Ls https://raw.github.com/thekompanee/fuubar/master/certs/thekopanee.pem)>


```

```ruby
RSpec.configure do |config|
  config.fuubar_progress_bar_optoins = { :format => 'My Fuubar! <%B> %p%% %a' }
end



```

```
```
