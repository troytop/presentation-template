<!-- .slide: data-state="cover" id="lightning-0" data-menu-title="Broadening the CF Base" data-timing="20" -->
<div class="title">
    <h1>Broadening the Base</h1>
    <h2>Increasing Options for Deploying Cloud Foundry</h2>
</div>

<div class="row presenters">
    <div class="presenter presenter-1">
        <h3 class="name">Troy Topnik</h3>
        <h3 class="job-title">Sr. Product Manager</h3> 
        <h3>SUSE Cloud Appliation Platform</h3>
        <h3 class="email"><a href="mailto:troy.topnik@suse.com">troy.topnik@suse.com</a></h3>
    </div>
</div>


<!-- .slide: data-state="section-break" id="lightning-1" data-timing="30s" data-menu-title="SUSE gets into Cloud Foundry" -->
# SUSE is building a Cloud Foundry! 
## ...but we can't use someone else's OS


<!-- .slide: data-state="normal" id="lightning-2" data-menu-title="SUSE Stemcells" data-timing="30s" -->
# openSUSE and SUSE Linux Enterprise
* "Factory First" - openSUSE then SLE 
* upstream work will be on openSUSE
* SUSE Cloud Application Platform will ship with SLE  


<!-- .slide: data-state="normal" id="lightning-3" data-menu-title="Trusty Stemcell" data-timing="30s" -->
# Our Trusty Stemcell

Cloud Foundry has (almost) always been built on Ubuntu  
* 10.04 (Lucid) from original open source release
* 14.04 (Trusty) since 2014

Now you can run on openSUSE 42.3 BOSH stemcells
* landing upstream very soon
* anyone who wants to can use it!


<!-- .slide: data-state="normal" id="lightning-4" data-menu-title="Trusty Stack" data-timing="30s" -->
# Our Trusty Stack

## Stacks are a very cool. Let's use more than one!

Upstream buildpacks work on cflinuxfs2, openSUSE, and SLE stacks
* we just have to build the binaries
* ALL the binaries - lots of languages, lots of versions

## SUSE can help with this. 


<!-- .slide: data-state="normal" id="lightning-5" data-menu-title="SUSE OBS" data-timing="30s" -->
# SUSE Open Build Service (OBS) 

* we build a LOT of packages  
* ...in a lot of formats (rpm, deb, tgz)
* ...for a lot of platforms (x86_64, arm, zSystem)

## We will be building for openSUSE and SLE, but we could do others.


<!-- .slide: data-state="section-break-4" id="lightning-6" data-menu-title="CF Containerization" data-timing="30s" -->
# Cloud Foundry on Kubernetes 
## It can be done
## We know, we've done it twice 


<!-- .slide: data-state="normal" id="lightning-7" data-menu-title="What we're building" data-timing="30s" -->
# SUSE Cloud Application Platform

* Containerized Cloud Foundry
* build from BOSH releases
* on SUSE Linux Enterprise
* running on Kubernetes (CaaS Platform and others)
* using Helm for lifecycle management and data services 


<!-- .slide: data-state="normal" id="lightning-8" data-menu-title="Open, open source" data-timing="30s" -->
# SUSE. The open, open source company. 

ActiveState Stackato - an early fork
* interesting innovations (router, fs service, DEA)
* not easily integrated upstream 

HPE Helion Stackato - certified CF distribution
* several projects open sourced
* ...but not everything, and not completely

SUSE SCF, Stratos UI, CF Universal Service Broker, and Fissile 
* proven commitment to open source
* Help us innovate! 


<!-- .slide: data-menu-title="SUSE logo" id="SUSE-logo" data-state="green-bg" -->
<img data-src="images/SUSE/SUSE-logo-white.png"
     alt="SUSE&reg; logo"
     style="width: 25%; height: 25%; margin-top: 20%;"
     class="full-slide" />


