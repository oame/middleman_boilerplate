# middleman_boilerplate

## Installation
```
$ bundle install --path vendor/bundle --binstubs=.bundle/bin --without production:staging
$ bower install
$ middleman server
```

## Deploy
```
$ middleman build
$ middleman deploy
```

## Bootstrap with Sublime Text 3

Nettus+ Fetch configfile
```json
{
  "files":
  {
    "jquery": "http://code.jquery.com/jquery.min.js",
    "jquery.easing": "http://gsgd.co.uk/sandbox/jquery/easing/jquery.easing.1.3.js",
    "jquery.mousewheel": "https://raw.github.com/brandonaaron/jquery-mousewheel/master/jquery.mousewheel.js"
  },
  "packages":
  {
    "html5_boilerplate": "https://github.com/h5bp/html5-boilerplate/zipball/master",
    "middleman_boilerplate": "https://github.com/oame/middleman_boilerplate/zipball/master"
  }
}
```
