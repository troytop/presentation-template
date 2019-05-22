<!-- .slide: data-state="cover" id="cover-page" data-timing="20" data-menu-title="Cover slide" -->
<div class="title">
    <h1>A developer workflow for Kubernetes?</h1>
    <h2>We've already got one.</h2>
</div>

<div class="row presenters">
    <div class="presenter presenter-1">
        <h3 class="name">Troy Topnik</h3>
        <h3 class="job-title">Product Manager</h3>
        <h3 class="email"><a href="mailto:troy.topnik@suse.com">troy.topnik@suse.com</a></h3>
    </div>
</div>



<!-- .slide: data-state="normal" id="abstract" data-menu-title="Abstract" -->
## Abstract:

Kubernetes is a superb platform for containers but is it the right interface
for people writing code? Numerous projects have sprung up over the past two
years to simplify the deployment of code to containers, but what if the best
solution was an opinionated Platform-as-a-Service framework that's been around
for years? This talk presents the case that with the Eirini and Quarks
projects, Cloud Foundry makes an ideal developer interface to Kubernetes and a
good structured platform for cooperating with the IT Operators who manage
Kubernetes infrastructure.



<!-- .slide: data-state="normal" id="why" data-menu-title="Why am I here?" -->

## Why am I here?
  * to point out a wheel that doesn't need reinventing 
  * to be evangelical about the software I've been working with for eight years


<!-- .slide: data-state="normal" id="assumptions" data-menu-title="What can we assume?" -->

## Assumptions: What can we agree on?
  * containers are a great way to deliver software
  * containers are replacing virtual machines for a lot of use cases
  * Kubernetes is the most widely adopted orchestrator for containers
  * Kubernetes seems to be displacing IaaS platforms like Open Stack
  * Kubernetes has as much of a learning curve as its predecessors



<!-- .slide: data-state="normal" id="whats-happening" data-menu-title="What do we see now?" -->

## What we are seeing now:
  * proliferation of "last mile" application delivery mechanisms for Kubernetes
  * "container first" mindset
  * strong ties to Git in developer tooling
  * competing platforms, competing APIs



<!-- .slide: data-state="normal" id="our-quest" data-menu-title="Searching for the Grail" -->

## Searching for the Holy Grail
  * easy to learn and easy to use
  * enough flexibility to deploy different types of app
  * not tied to one programming language / web framework 
  * ... or IDE
  * ... or source control tool 
  * ... or vendor!
  * scalable (up AND down)
    * apps AND organizations
  * secure
  * a platform that lets Ops and Dev work together effectively

"We have been charged by Management with a sacred quest. If you will give us a budget and a team of engineers, you can join us in our quest for the Ultimate Application Delivery Platform"



<!-- .slide: data-state="normal" id="our-quest" data-menu-title="Searching for the Grail" -->

## Platform-as-a-Service Primer 
  * We used to deliver web apps on shared hosts with FTP
  * AWS gave us cheap virtual machines in the cloud
  * Engine Yard was one of the first major multi-tennant PaaS for Rails
  * Google App Engine followed with a similar model but for Java, Node, and Python
  * Heroku gave us extensibility with language buildpacks
  * VMWare gave us an open source PaaS framework: Cloud Foundry
  * dotCloud gave us docker (then became Docker)



<!-- .slide: data-state="normal" id="what-then" data-menu-title="Losing our way" -->

## Then what?
  * ... and then we all forgot about PaaS BECAUSE CONTAINERS!!!
  * and now we are adding PaaS functionality back to CaaS



<!-- .slide: data-state="normal" id="what-now" data-menu-title="Finding our way" -->

## What we have got already

    S: Well, I'll ask 'im, but I don't think 'e'll be very keen-- 'e's already got
       one, you see?
    A: Are you *sure* he's got one?
    S: Oh yes, it's ver' naahs.


