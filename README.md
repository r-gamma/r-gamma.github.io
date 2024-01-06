# Landing Page Jekyll theme

Jekyllのテーマで作成されています。  
参照 [landing-page bootstrap theme ](http://startbootstrap.com/templates/landing-page/)

## How to use

rubyが必要です

    brew install rbenv ruby-build
    rbenv init
    echo 'eval "$(rbenv init - zsh)"' >> ~/.zshrc
    curl -fsSL https://github.com/rbenv/rbenv-installer/raw/main/bin/rbenv-doctor | bash
    rbenv install --list
    rbenv install {x.x.x}
    rbenv global {x.x.x}
    ruby --version

jekyllが必要です

    bundle install
    gem install bundler jekyll

起動します

    bundle exec jekyll serve

 - Create posts to display your services. Use the follow as an example:

```txt
---
layout: default
img: ipad.png
category: Services
title: The service title
---
The description of this service
```

## Demo
View this jekyll theme in action [here](https://swcool.github.io/landing-page-theme)

## Screenshot
![screenshot](https://raw.githubusercontent.com/swcool/landing-page-theme/master/img/screenshot.png)

===

For more Jekyll details, read [documentation](http://jekyllrb.com/).
This Jekyll theme used [Freelancer Jekyll theme](https://github.com/jeromelachaud/freelancer-theme/) as reference.

## License
The contents of this repository are licensed under the [Apache
2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

## Version
1.0.1
