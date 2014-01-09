# Flexget Config and HTML Templates
***
## v. 2

### Changes

- Various stylistic changes (dropped support for dark theme, can still be used with html_enhanced_dark.template)

 - Stars look a little nicer
 - A minor selection of TV shows now use some coloring  to match their poster/logo
 - Added a separator between downloads
- Rudimentary support for movies
 - No support for fanart, but it's someting I'm looking into and trying to figure out

### [Check it out](http://dustinschau.com/drop/flexget/test-email.html)
***
# v1

[Flexget](http://flexget.com/) is an excellent tool for automatic downloading of tv shows, along with other content (such as movies). However, it was, for me at least, marginally difficult to get configured in a way that I was pleased with. 

As such, I've included my config.yml file (this is the file used by flexget to run any tasks that are configured), as well as two HTML email themes, light and dark, that I created as the default HTML template didn't suit my needs. 

View the [dark theme](http://jsfiddle.net/YLrd7/1/embedded/result/) and the [light theme](http://jsfiddle.net/YLrd7/2/embedded/result/). 

A few things to consider with the HTML themes: 

1.  They're pretty dependent on the tvdb\_fanart\_url. If the tv shows doesn't have fan art defined, I would recommend creating an account for the tvdb, and adding some for the show.
2. There are media queries included for iPhones/small screen devices that attempt to alter the styling to better fit the small screens. 
3. I haven't really made any attempt to make the css styling and structure render better in some of the less well-rendering e-mail clients. I have tested in the default Mail apps on OS X and iOS, and it appears to work well with both of those. That is sufficient for my needs. 