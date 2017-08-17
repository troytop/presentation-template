<!-- .slide: data-state="cover" id="cover-page" data-timing="20" -->
<div class="title">
    <h1>SUSE Cloud Application Platform</h1>
    <h2>Roadmap</h2>
</div>

<div class="row presenters">
    <div class="presenter presenter-1">
        <h3 class="name">Troy Topnik</h3>
        <h3 class="job-title">Sr. Product Manager, SUSE Cloud Appliation Platform</h3>
        <h3 class="email"><a href="mailto:troy.topnik@suse.com">troy.topnik@suse.com</a></h3>
    </div>
    <div class="presenter presenter-2">
        <h3 class="name">Ronald Nunan</h3>
        <h3 class="job-title">Sr. Product Manager, SUSE Cloud Appliation Platform</h3>
        <h3 class="email"><a href="mailto:rnunan@suse.com">rnunan@suse.com</a></h3>
    </div>
</div>


<!-- .slide: data-state="normal" id="nested-lists" data-timing="20s" data-menu-title="Standard text slide" -->
## Slide title

*   First-level bullet
    *   Second-level bullet
        *   Third-level bullets are a bad idea
            *   Fourth-level bullets are a terrible idea

Before loading up your presentation with bulleted lists, make sure to
[read up on whether that's a good idea](https://www.google.com/search?q=slides+bullets).


<!-- .slide: data-state="section-break" id="section-break-1" data-timing="10s" -->
# Section break (style 1)
## `<h2>` works here too


<!-- .slide: data-state="section-break-2" id="section-break-2" data-timing="10s" -->
# Section break (style 2)


<!-- .slide: data-state="section-break-3" id="section-break-3" data-timing="10s" -->
# Section break (style 3)


<!-- .slide: data-state="section-break-4" id="section-break-4" data-timing="10s" -->
# Section break (style 4)


<!-- .slide: data-state="normal" id="syntax-highlighting" -->
## Code syntax highlighting

Works out of the box using [`highlight.js`](https://highlightjs.org/)
and a custom color theme with official SUSE colors:

```js
Reveal.addEventListener('somestate', function() {
    // TODO: Sprinkle magic
}, false );
```

in different languages:

```ruby
# Ping with 5 seconds timeout and a single attempt
def ping! node
  command = ["ping", "-q -c 5 -w 5 #{node.ip}"]
  result = exec!(*command)
  if result.exit_code.nonzero?
    raise PingError.new(command, result.output)
  end
  result, :foo
end
```


<!-- .slide: data-state="section-break" id="full-screen-images" data-timing="10s" -->
# Full screen images


<!-- .slide: data-state="blank-slide" class="full-screen" id="full-screen-image-1" data-menu-title="Full screen image" data-timing="10s" -->
<a title="By Fraser Hart (http://www.hermitagebay.com) [GFDL (http://www.gnu.org/copyleft/fdl.html) or CC BY-SA 3.0 (http://creativecommons.org/licenses/by-sa/3.0)], via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File%3ABeach_pano.jpg">
    <img alt="Beach pano" src="images/beach-pano-16x9.jpg"/>
</a>


<!-- .slide: data-state="blank-slide" class="full-screen" id="full-screen-image-2" data-menu-title="Tall full screen image" data-timing="10s" -->
<a title="By Fraser Hart (http://www.hermitagebay.com) [GFDL (http://www.gnu.org/copyleft/fdl.html) or CC BY-SA 3.0 (http://creativecommons.org/licenses/by-sa/3.0)], via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File%3ABeach_pano.jpg">
    <img alt="Beach pano" src="images/beach-pano-tall.jpg"/>
</a>


<!-- .slide: data-state="blank-slide" class="full-screen" id="full-screen-image-3" data-menu-title="Wide full screen image" data-timing="10s" -->
<a title="By Fraser Hart (http://www.hermitagebay.com) [GFDL (http://www.gnu.org/copyleft/fdl.html) or CC BY-SA 3.0 (http://creativecommons.org/licenses/by-sa/3.0)], via Wikimedia Commons" href="https://commons.wikimedia.org/wiki/File%3ABeach_pano.jpg">
    <img alt="Beach pano" src="images/beach-pano-wide.jpg"/>
</a>
