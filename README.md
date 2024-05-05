# Run the site
bundle exec jekyll serve

# To archive past year work shop
* Create a folder named _y{year}
* In the _config.yml file
  * find `collections` object
  * add new element:
```
y{year}:
    output: true
    permalink: /{year}/:name
```
