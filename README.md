# Videojs::Ng::Socialshare

Adds social sharing buttons to the video.js for Facebook and Twitter.

This gem bundles the upstream distribution for use with the Ruby on Rails framework. The version number of
the gem always tracks the upstream javascript release and the gem itself doesn't provide any additional
methods or helpers. If a need for helpers arises in the future they will be developed as a separate gem
with this one as its dependency. Should a gem bug be discovered an additional version identifier will be
appended and incremented after the upstream version number.

## License
videojs-ng-socialshare gem and changes made to the video.js socialShare plugin required for rails are licensed under ISC.

The original video.js socialshare plugin code distributed with this gem is licensed under [MIT](https://tldrlegal.com/license/mit-license)
You can find the plugins license file in the vendor directory, changes made to the original code base are as follows:

 - none so far

Please note, the initial plugin code of socialShare lives under

 - https://github.com/jmccraw/videojs-socialShare

this gem however packages:

 - https://github.com/AdamTyler/videojs-socialShare

which is an updated and extended fork of the initial repository,
most significant change fixes the plugin for video.js 6+

licensing has been unchanged between that fork and the origin repository.

Since both repositories don't do releases of recent changes the commit ID used to bundle
the plugin from AdamTyle/videojs-socialShare repository is: 75fd0d55e9a801babc281d19b017229325bf5664

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'videojs-ng-socialshare'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install videojs-ng-socialshare

## Usage

Include the plugin in your `application.js`:

  //= video-socialshare

Include the stylesheet in `application.css':

  *= video-socialshare

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/koparo/videojs-ng-socialshare.
