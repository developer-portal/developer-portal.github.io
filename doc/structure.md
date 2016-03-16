---
section: doc
page_menu_hl: structure
layout: documentation
---

# Website Structure

The portal is divided into **sections**. Each section contains **subsections**, and each subsection has several **pages**.

## Section

**Examples:** Get Tools, Languages and Databases, ...

<div class="row">
  <div class="col-md-10">
    <img src="/static/img/section.png" class="img-responsive img-thumbnail">
  </div>
</div>

## Subsection

**Examples:** Vagrant, Docker, Python, Ruby, ...

<div class="row">
  <div class="col-md-10">

    <img src="/static/img/subsection.png" class="img-responsive img-thumbnail">
  </div>
</div>

## Page

**Examples:** About Vagrant, Vagrant with libvirt provider, Vagrant with VirtualBox provider, ...

Pages contain the actual content. Contributors only need to create and edit pages. Pages are represented by **Markdown files** with special **YAML header**, which defines section, subsection, and information used in title - name and description.

### Example page file

```
---
name: Docker in Fedora
subsection: docker

section: tools
description: Platform for distributed applications.
---

# Docker
Docker is a platform for developers and sysadmins to develop, ship, and run applications ...

## Getting Started with Docker
To install and run Docker ...
```

*More information about files is in the [File Structure](/doc/file-structure.html) section.*
