Drop .chef/plugins/knife/source_ingredient_git.rb
into your .chef/plugins/knife directory and run:

```
knife source ingredient git
```

:file_cache_path and :data_bag_path must writable and might need to be set in your knife.rb

The latest available versions of git for windows and osx will be downloaded into
your file_cache_path and your data bag path will get a git directory
created which will be populated with data bag items for each version
of git that is available.

