---
layout: single
author_profile: true
title: Contact me
permalink: /contact/
---

<form id="contactform" method="POST">
  <input type="text" name="name" placeholder="Your name" >
  <input type="text" name="_replyto" placeholder="Your email" >
  <input type="hidden" name="_subject" value="Website contact" />
  <textarea name="message" placeholder="Your message"></textarea>
  <button type="submit">Submit</button>
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'leonreteig' + '@' + 'gmail' + '.' + 'com');
</script>
