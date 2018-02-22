---
section: doc
page_menu_hl: file-structure
layout: documentation
---

# File Structure

*You might want to see the [Website Structure](/doc/structure.html) section before reading this.*

Each file starts with a special **YAML header**, which defines information like section, subsection, title, or description.
The actual content is written in **Markdown**.

## YAML header
You need to set some variables in each file to make it work with the portal.

### Examples

#### Main Page

```
---
title: Writing Web Applications
subsection: web-app

section: start-sw
description: An overview of technologies that can be used to write a web application. Including PHP, Django, and Ruby on Rails.
---

# Page Header
Lorem ipsum dolor sit amet...
```

#### Other Pages

```
---
title: Writing Web Applications
subsection: web-app
---

# Page Header
Lorem ipsum dolor sit amet...
```

### Variables
* **title** (all pages) - Name of the page displayed in menu.
* **subsection** (all pages) - ID of subsection. Setting this will:
  * add the page to the '*list of pages*' menu.
* **section** (main page only) - ID of section. Setting this will:
  * add the page to the '*list of subsections*' menu,
  * mark this page as the main page of your subsection,
  * display the *title* and *description* of this file in the '*subsection header*'.
* **description** (main page only) - Description of the subsection.
* **order** (optional) - A number, used to sort links in the '*list of pages*' menu.

#### Sections IDs

<div class="row">
  <div class="col-md-10">
    <table class="table table-striped table-bordered table-main">
      <tr>
        <th> Section Name </th>
        <th> Section IDs </th>
      </tr>
      <tr>
        <td> Start a Project </td>
        <td>
          <ul class="list-unstyled">
            <li>start-sw</li>
            <li>start-hw</li>
            <li>start-tips</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td> Get Tools </td>
        <td>
          <ul class="list-unstyled">
            <li>tools</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td> Languages & Databases </td>
        <td>
          <ul class="list-unstyled">
            <li>tech-languages</li>
            <li>tech-database</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td> Deploy & Distribute </td>
        <td>
          <ul class="list-unstyled">
            <li>deployment</li>
          </ul>
        </td>
      </tr>
    </table>
  </div>
</div>

#### Subsections IDs
You can use any ID for your subsection - it should make sense and must not be used before. For example, a subsection about Docker could use ID *docker*, and a subsection about Creating Web Applications could use ID *web-app*.
