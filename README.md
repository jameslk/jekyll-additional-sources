# Jekyll Additional Sources Plugin

Allows you to use additional directories as source directories. Each directory is merged with the last.
If a file has the same name in multiple directories, it will be overwritten by the last defined source location.

## Why?
I felt it was awfully messy to keep all your blog's source files under the root directory. This plugin allows you to define another directory (if not multiple
directories) where your site's sources can be placed instead to keep things clean.

## Installation
Copy `_plugins/jekyll-additional-sources.rb` into your project's `_plugins` directory.

## Usage
Use the `additional_sources` config setting to define a list of additional source directories.

```yaml
# _config.yml

additional_sources:
  - "_src/"
  - "_another_src_dir/"
```
