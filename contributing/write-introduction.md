---
layout: contributing
page_menu_hl: write
page_submenu_hl: introduction
section: contributing
---

# **2.** Write

<div class="row">

  <div class="col-md-3">
    <div class="panel panel-success">
      <div class="panel-body">
        <span class="glyphicon glyphicon-ok" style="color:green;font-size:30px"></span>
        <h4>Fedora-specific </h4>
      </div>
    </div>
  </div>
  <div class="col-md-3">
    <div class="panel panel-success">
      <div class="panel-body">
        <span class="glyphicon glyphicon-ok" style="color:green;font-size:30px"></span>
        <h4>Quickstart </h4>
      </div>
    </div>
  </div>
  <div class="col-md-3">
    <div class="panel panel-success">
      <div class="panel-body">
        <span class="glyphicon glyphicon-ok" style="color:green;font-size:30px"></span>
        <h4>Reference </h4>
      </div>
    </div>
  </div>
  <div class="col-md-3">
    <div class="panel panel-danger">
      <div class="panel-body">
        <span class="glyphicon glyphicon-remove" style="color:#c00;font-size:30px"></span>
        <h4>Documentaion </h4>
      </div>
    </div>
  </div>
</div>

## Style and Formatting

* Please use `$ sudo ...` for commands requiring root password or root user.
* Use the names of upstream project and files properly - e.g. `Makefile` will have capital M.
* Referencing commands and names of binaries that would be ran in command line should be done using back-ticks ``.
* Add empty lines before and after headlines and code blocks.
* Format headlines as normal sentences e.g. About my program called Program, *not* About My Program Called Program
* Take a look at [Github markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### Internal Links

To reference a page in this repository, use the full path and replace `.md` extension to `.html`:

e.g. to reference `/tech/tools/vagrant/vagrant-libvirt.md` write `[Vagrant with libvirt](/tech/tools/vagrant/vagrant-libvirt.html)`

## YAML Header
All files need to start with a special YAML header. Please read [Documentation / File Structure](/doc/file-structure.html) for more details.
