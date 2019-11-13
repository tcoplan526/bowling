---
title: Contact
date: 2019-11-13T09:05:20.785Z
draft: false
categories: Contact
author: SNHUSBC
authorImage: bowling/static/snhusbc.jpg
image: news.jpg
type: post
weight: 10
---
<p> Please leave your name, email and a message for us and we will get back to you.  If you wish to be contacted by phone you can leave your phone number in the message.
</p>
<form name="contact" method="POST" netlify-honeypot="bot-field" data-netlify="true">
  <p class="hidden">
    <label>Don’t fill this out if you're human: <input name="bot-field" /></label>
  </p>
  <p>
    <label>Your Name: <input type="text" name="name" style=/></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" style=/></label>
  </p>
    <label>Message: <br><textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>