---
title: Contact
subtitle: Contact use
img_path: images/5.jpg
menus:
  layouts:
    title: contact
    weight: 1
template: page
---
<form name="contact" method="POST" netlify data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>

\    <button type="submit">Send</button>
  </p>
</form>