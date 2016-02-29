---
layout: post
title: Asynchronous Email in Flask
---

Something to keep in mind when sending an email confirmation in python is that the process will block.
This means that your application will screech to a halt while your email is sending. To avoid this, it is possible
to execute the sending of your email in a thread, asynchronously. Miguel Grinberg has a great tutorial on how to do this 
<a target="_blank" href="http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-xi-email-support">here</a>.