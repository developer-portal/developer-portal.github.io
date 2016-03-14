---
section: doc
page_menu_hl: structure
layout: documentation
---

# Website Structure

## Structure

<img src="/static/img/website-structure.png" width="600px">

### Sections

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

### Pages
You can use any ID for your page - it should make sense and must not be used before. For example, a page about Docker could use ID *docker*, and a page about Creating Web Applications could use ID *web-app*.

## Example Usage
Every file with content should start with a YAML header. There is a small difference in headers for the *home page* and *other pages*.

### *Home Page* Example

```
---
name: Writing Web Applications
page: web-app

section: start-sw
description: An overview of technologies that can be used to write a web application. Including PHP, Django, and Ruby on Rails.
---
```

### *Other Pages* Example

```
---
name: Writing Web Applications
page: web-app
---
```
