---
layout: default
title: Events
permalink: /events/
---
<br>
<form class="contact-form" method="post" action="https://formspree.io/{{site.data.settings.client.email}}">
  <input type="text" name="name" placeholder="Name" required>
  <input type="email" name="_replyto" placeholder="Email" required>
  <input type="text" name="event" placeholder="Event Date" required>
  <textarea name="Message" placeholder="Message"></textarea>
  <!-- Cloud cannon settings field -->
  <div class="hidden">
    <input type="hidden" name="_to" value="{{site.data.settings.client.email}}">
    <input type="hidden" name="_subject" value="Contact Message From Your Vyral Video Blog">
    <input type="text" name="_gotcha">
  </div>

  <input type="submit" value="submit">
</form>
