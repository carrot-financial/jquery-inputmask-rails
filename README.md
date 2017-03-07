# jquery-inputmask-rails

This was forked from knapo and altered slightly to make it compatible with Rails 5.

jquery-inputmask-rails integrates [jquery.inputmask](https://github.com/RobinHerbots/jquery.inputmask) with Rails 5

jquery.inputmask version: <b id="jquery.inputmask-version">3.1.x</b>

### Installation

Add

``` ruby
gem 'jquery-inputmask-rails', github: 'carrot-financial/jquery-inputmask-rails'
```

to your `Gemfile`

and

```javascript
//= require inputmask
//= require jquery.inputmask
```

to your `app/assets/javascripts/application.js` or other js manifest file.

Optional extensions (these are super helpful):

```javascript
//= require inputmask.extensions
//= require inputmask.date.extensions
//= require inputmask.phone.extensions
//= require inputmask.numeric.extensions
//= require inputmask.regex.extensions
```
