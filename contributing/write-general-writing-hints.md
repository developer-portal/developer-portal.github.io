---
layout: contributing
page_menu_hl: write
page_submenu_hl: hints
section: contributing
---


# General writing hints

##  Keep it simple

Don't use complicated sentences. Not everyone reading the documentation will be fluent in English, and if the solution texts get translated, it might be to Japanese, which is a language so fundamentally different that anything even a little bit complicated turns into a translation nightmare.

### Simple from technical standpoint

Keep the doc simple from a **technical standpoint** too. Not everyone reading the documentation will be an experienced admin/user.

## Avoid shorthands

They're just too informal.

### Bad example:

> The update won't be available...

### Good example:

> The update will not be available...

## Be direct

Avoid passive voice.

### Bad example:

> This can be fixed by...

### Good example:

> You can fix this issue by...

## Tell the user what is going on

When you tell users to run a set of commands, tell them what is going on. This mostly applies to cases where the documentation text contains some procedure (a set of commands) to do some complicated stuff. When that happens, don't just put in the commands, but explain them.

### Bad example:

> ```
> $ sudo systemctl disable firewalld
> $ sudo systemctl stop firewalld
> $ sudo cp PREUPGRADE_DIR/cleanconf/etc/sysconfig/iptables /etc/sysconfig/iptables
> ```
> etc.

### Good example:

> First, disable and stop the firewalld service:
> ```
> $ sudo systemctl disable firewalld
> $ sudo systemctl stop firewalld
> ```
> Then, copy the `cleanconf/etc/sysconfig/iptables` configuration file into your system's `/etc/sysconfig/` directory:
> ```
> $ sudo cp PREUPGRADE_DIR/cleanconf/etc/sysconfig/iptables /etc/sysconfig/iptables
> ```
> etc.


If this makes the particular documentation too long, you could create a separate page about it and provide a link to the user instead.

## Be sure

If we say things like "this should be in...", it makes us sound like we don't even know what's actually going on.

### Bad example:

> You should be able to find this list in `/etc/whatever/list`.

### Good example:

> The list is located in `/etc/whatever/list`.

## How to document an issue in more versions

In case you want to document one issue for more versions of the product, while there are small differences in each version, create one article for the most current version and use notes to describe differences for other versions.
