<!-- .slide: data-state="cover" id="cap-roadmap-start" data-menu-title="Broadening the CF Base" data-timing="20" -->
<div class="title">
    <h1>Broadening the Base</h1>
    <h2>Increasing Options for Deploying Cloud Foundry</h2>
</div>

<div class="row presenters">
    <div class="presenter presenter-1">
        <h3 class="name">Troy Topnik</h3>
        <h3 class="job-title">Sr. Product Manager, SUSE Cloud Appliation Platform</h3>
        <h3 class="email"><a href="mailto:troy.topnik@suse.com">troy.topnik@suse.com</a></h3>
    </div>
</div>


<!-- .slide: data-state="normal" id="cap-intro" data-timing="20s" data-menu-title="SUSE Cloud Application Platform" -->
# SUSE Cloud Application Platform

Speed delivery and streamline lifecycle management of traditional and

cloud-native applications with a modern application delivery platform.
* Accelerate innovation with a single platform for rapid application delivery at scale.
* Reduce complexity and improve IT efficiency with a solutions that is easy to install,
scale and maintain
* Maximize return on your investment with enterprise-ready, industry leading
 technologies

### 100% - Community built and enterprise-ready
### 1 - Platform that brings together Cloud Foundry and Kubernetes
### Reduce - Installation and management complexity with containerized distribution


<!-- .slide: data-state="normal" id="cap-strategy" data-timing="20s" data-menu-title="SUSE CAP Strategy" -->

## Platform Strategy

<br>
Produce and support a modern, open source application delivery platform to:
* Support software development and operations teams streamlining the lifecycle
  management of traditional and new cloud native applications
* Bring together industry-leading Cloud Foundry and Kubernetes
* Facilitate DevOps process integration to accelerate innovation, improve IT
  responsiveness, and maximize return on investment using market leading OSS
  projects


<!-- .slide: data-state="section-break" id="cap-big-picture" data-menu-title="SUSE CAP Big Picture" data-timing="10s" -->

# SUSE Linux Enterprise
# + Kubernetes
# + Cloud Foundry
# = SUSE Cloud Application Platform


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

<br>
Software developers focus on code, not infrastructure
* self-service – application code pushed via API
* increases the pace of software development

<br>
Operators deliver a service, not individual deployments
* systematic DevOps – standard process provided by the platform
* manages running code in public and private clouds
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
<div class="slide-section" style="float: right; clear: both;">
    <img data-src="images/stratos-ui-app.png" style="width: 100%;" />
</div>
<br>
CF UI deployed via Helm or as a Cloud Foundry app

<br>
Open source on Github:  SUSE/stratos-ui

<br>
User and Admin views

<br>
Supports multiple CF API endpoints


<!-- .slide: data-state="normal" id="uaa" data-timing="20s" data-menu-title="CF UAA" -->
# UAA (Cloud Foundry Auth Server)

<br>
Certified Cloud Foundry component

<br>
Allows stand-alone deployments separately from SUSE CF

<br>
SUSE CF configurable to use existing/separate OAuth2 server

<br>
UAA service can be used for OpenID Connect auth for other components (e.g. Kubernetes role-based access control)


<!-- .slide: data-state="normal" id="portus" data-timing="20s" data-menu-title="Portus" -->
# Portus + Container Registry

<div class="slide-section" style="float: right">
    <img data-src="images/portus.png" style="width: 800px;" />
</div>
<br>
<br>
Providing a local registry server for developers

Portus will provide the UI and user management


<!-- .slide: data-state="normal" id="future-services" data-timing="20s" data-menu-title="Post 1.0 Services" -->
# Post-1.0 Services

SUSE CAP gaining services that compliment a DevOps workflow

<br>
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
