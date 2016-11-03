[mimilau.github.io](http://mimilau.github.io)

**In experimental Stage**

## Run Jekyll Locally

```
gem install jekyll
```
cd to the working folder, then
```
jekyll serve
```

## Create a Post
```
rake post title="Hello World"
```

## Create a Page
```
rake page name="about.md"
```
Create a nested page:
```
rake page name="pages/about.md"
```
Create a page with a "pretty" path:
```
rake page name="pages/about"
# this will create the file: ./pages/about/index.html
```

### Usage

For all usage and documentation please see: <http://jekyllbootstrap.com>

Theme support: [Travelogue](https://github.com/SalGnt/Travelogue)

### License

[MIT](http://opensource.org/licenses/MIT)
