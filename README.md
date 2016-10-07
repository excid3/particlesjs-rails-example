# Particles.js with Ruby on Rails

By [Chris Oliver](http://excid3.com) from [GoRails](https://gorails.com)

## Instructions

Here's how you can use this in Rails.

1. Add particles.min.js to `/vendor/assets/javascripts` and add `//= require particles.min` to `application.js`
2. Add `<div id="particles-js"></div>` to your view
3. If you want a static config, create a javascript file like
   [app/assets/javascripts/main.js](https://github.com/excid3/particlesjs-rails-example/blob/master/app/assets/javascripts/main.js) and just write your JSON config as the second argument.
4. If you want a dynamic config, you can create a JSON endpoint and
   return the JSON config by specifying the url as the second parameter
   in the `particleJS()` call

