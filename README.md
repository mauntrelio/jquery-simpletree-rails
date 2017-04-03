# jquery-simpletree-rails

This gem provides the jquery simpleTree plugin found at https://github.com/mauntrelio/jquery-simpletree/ for the Rails asset pipeline.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'jquery-simpletree-rails'
```

And then execute:

```bash
$ bundle install
```

Add this to 'app/assets/javascripts/application.js':

```
//= require simpleTree/jquery.simpletree
```

Add this to 'app/assets/stylesheets/application.css':

```
*= require simpleTree/_simpleTree
```

Or, if you use scss:

```scss
@import 'simpleTree/simpleTree';
```

to 'app/assets/stylesheets/application.scss'.

That's it!

Now, to apply the treeview, you need to manage from your JavaScript code, for instance:

```javascript
$(document).ready(function(){
	$('ul.treeview').simpleTree();
});

```

Please have a look to https://github.com/mauntrelio/jquery-simpletree/ for further information about APIs (collapse, expand, repaint, etc..);
