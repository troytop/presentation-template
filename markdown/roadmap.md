<!-- .slide: data-state="cover" id="cap-roadmap-start" data-menu-title="SUSE CAP Roadmap" data-timing="20" -->
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


<!-- .slide: data-state="normal" id="cap-strategy" data-timing="20s" data-menu-title="SUSE CAP Strategy" -->

## Platform Strategy

Produce and support a modern, open source application delivery platform to:
* Support software development and operations teams streamlining the lifecycle
  management of traditional and new cloud native applications
* Bring together industry-leading Cloud Foundry and Kubernetes
* Facilitate DevOps process integration to accelerate innovation, improve IT
  responsiveness, and maximize return on investment using market leading OSS
  projects


<!-- .slide: data-state="section-break" id="cap-big-picture" data-menu-title="SUSE CAP Big Picture" data-timing="10s" -->

# Kubernetes + Cloud Foundry 
#   ==>  SUSE Cloud Application Platform


<!-- .slide: data-state="normal" id="cap-high-level" data-timing="20s" data-menu-title="SUSE CAP High-Level Goals" -->

## SUSE Cloud Application Platform

Accelerate application delivery with SUSE Cloud Foundry
* code-centric and container-centric deployment methods
* systematic workflow controls and platform access via API

Improve IT efficiency with a lean platform
* containerized platform roles reduce memory footprint
* Kubernetes provides faster scaling and fault recovery

Use industry-leading technologies
* manage Cloud Foundry and services using kubectl and helm
* proven reliability with SUSE Linux Enterprise throughout the stack


<!-- .slide: data-state="normal" id="cap-software-landscape" data-timing="20s" data-menu-title="SUSE CAP Software Landscape" -->
## Software Landscape 

<div class="slide-section">
    <img data-src="images/software-landscape.svg" style="width: 100%;" />
</div>


<!-- .slide: data-state="normal" id="cap-build-deploy-manage" data-timing="20s" data-menu-title="SUSE CAP Build, Deploy, Manage" -->

## Build, Deploy, and Manage Cloud Native Applications

Software developers focus on code, not infrastructure
* self-service – application code pushed via API
* increases the pace of software development 

Operators build, run, manage, and scale apps easily 
* manages running code effectively in public and private clouds
* provides fault tolerance, health monitoring, routing, and load balancing


<!-- .slide: data-state="normal" id="cap-timeline" data-timing="20s" data-menu-title="SUSE CAP Timeline" -->
## Timeline 
<div class="slide-section">
    <img data-src="images/CAP-timeline.svg" style="width: 100%;" />
</div>


<!-- .slide: data-state="section-break-4" id="cap-ecosystem-services" data-menu-title="SUSE CAP Ecosystem Services" data-timing="10s" -->
# Ecosystem Services
## Containerized Software for DevOps 


<!-- .slide: data-state="normal" id="helm" data-timing="20s" data-menu-title="Helm" -->
# Kubernetes Helm
## Simplifying App and Service Deployment

System services are deployed via Helm:
* installs, upgrades and manages applications on Kubernetes
* Helm charts: YAML configuration and container images
* A community standard
* Included with Kubernetes in CaaS Platform

SUSE will:
* Include service brokers for popular databases available in upstream Kubernetes charts
* Continuously grow the service ecosystem with third parties using Helm


<!-- .slide: data-state="normal" id="stratos-ui" data-timing="20s" data-menu-title="CF Stratos UI" -->
# Stratos UI CF Web Interface
<div class="slide-section" style="float: right; clear: both; border: 1px black;">
    <img data-src="images/stratos-ui-app.png" style="width: 100%;" />
</div>
CF UI deployed via Helm or as a Cloud Foundry app

Open source on Github:  SUSE/stratos-ui

User and Admin views

Supports multiple CF API endpoints



<!-- .slide: data-state="normal" id="uaa" data-timing="20s" data-menu-title="CF UAA" -->
# UAA (Cloud Foundry Auth Server) 

Certified Cloud Foundry component

Allows stand-alone deployments separately from SUSE CF

SUSE CF configurable to use existing/separate OAuth2 server

UAA service can be used for OpenID Connect auth for other components (e.g. Kubernetes role-based access control)


<!-- .slide: data-state="normal" id="portus" data-timing="20s" data-menu-title="Portus" -->
# Portus + Container Registry

<div class="slide-section" style="float: right; clear: both; border: 1px black;">
    <img data-src="images/portus.png" style="width: 100%;" />
</div>

Providing a local registry server for developers

Portus will provide the UI and user management


<!-- .slide: data-state="normal" id="future-services" data-timing="20s" data-menu-title="Post 1.0 Services" -->
# Post-1.0 Services

SUSE CAP gaining services that compliment a DevOps workflow

CI/CD
* Concourse, Jenkins, other 
* Additional plugins for Cloud Foundry, Kubernetes, and Helm

Git
* GitLab, Gitea, or Github Enterprise

Misc
* Web-based IDE
* Object storage


<!-- .slide: data-menu-title="SUSE logo" id="SUSE-logo" data-state="green-bg" -->
<img data-src="images/SUSE/SUSE-logo-white.png"
     alt="SUSE&reg; logo"
     style="width: 25%; height: 25%; margin-top: 20%;"
     class="full-slide" />


<!-- .slide: data-state="normal" id="nested-lists" data-timing="20s" data-menu-title="Standard text slide" -->
## Slide title

*   First-level bullet
    *   Second-level bullet
        *   Third-level bullets are a bad idea
            *   Fourth-level bullets are a terrible idea

Before loading up your presentation with bulleted lists, make sure to
[read up on whether that's a good idea](https://www.google.com/search?q=slides+bullets).


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
