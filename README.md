# Fullcalendar::Rails

This gem is a simple rebundling of the contents of the JQuery FullCalendar plugin from Adam Shaw:

http://arshaw.com/fullcalendar/

I had created an earlier version of a demonstration of using FullCalendar in a rails app.  That code is available at:

https://github.com/bokmann/rails3_fullcalendar

But I have always disliked finding random files and copying them into a public directory.  So I made an asset gem for use with the asset pipeline.

## Installation

Add this line to your application's Gemfile:

    gem 'fullcalendar-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install fullcalendar-rails

## Usage

Add the following JavaScript file to `app/assets/javascripts/application.js`:

    //= require fullcalendar/fullcalendar.js
    //= require fullcalendar/gcal.js <--- In case you need Google Calendar support

Add the following stylesheet file to `app/assets/stylesheets/application.css`:

    *= require fullcalendar/fullcalendar.css

## Versioning

I am going to version this gem with the version of the fullceldnar code I use, adding an extra digit if I need to release any maintenance versions of the gem itself.  Therefore, since this is a first version of this gem and I'm starting by bundling version 1.5.3 of the fullcalendar code, this is version 1.5.3.0

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
