---
layout: contact
title: Contacts
---

<h1>Contacts</h1>

<ul>
   {% for contact in site.contacts %}
      <li>
            <a href="{{ contact.link }}" target="_blank" title="{{ contact.link-title }}">
            {{ contact.link-title }}
        </a>
      </li>
   {% endfor %}
</ul>>
