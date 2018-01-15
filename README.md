For an embedded systems class, I built a trail counter that counts the number of hikers 
crossing a trail footbride. I worked with an 
awesome [partner](https://www.linkedin.com/in/vinayakvedantam/).
You can read about our final system in our final report.


Since the project itself was pretty big and messy, I'm highlighting one section
I worked on by myself. These are the interesting bits of an emulated UART I wrote for
an [ST sensortile](http://www.st.com/en/evaluation-tools/steval-stlkt01v1.html) 
running [ChibiOS](http://www.chibios.org/dokuwiki/doku.php). It's not the most
efficient or secure code, but it was a fun challenge to write!
