---
title: Make First Contact
permalink: "/contact"
layout: about
---

<form action="https://getsimpleform.com/messages?form_api_token=<form_api_token>" method="post">

  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='{{ site.github.url }}/contact/contact-made.html' />

  <!-- all your input fields here.... -->
  <input type='text' name='test' />

  <input type='submit' value='Test form' />
</form>
