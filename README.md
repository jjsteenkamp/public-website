# Public Website - https://www.jsteenkamp.com

This project contains the source code for the https://www.jsteenkamp.com site. It is implemented as a [Jekyll](https://jekyllrb.com/) project which once built can be uploaded to a web host (e.g such as Amazon S3 / Cloudfront).  

## Building the project locally

* Install [Jekyll](https://jekyllrb.com/) on your workstation.
  
* In this directory, execute the command:

```
bundle exec jekyll serve
```

You should now be able to browse the site at http://localhost:4000. Once you are happy with the results, you can build the project with: 

```
bundle exec jekyll build
```

This will generate the site content to the `_site` sub directory. This can be uploaded to your host of choice.


