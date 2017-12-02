=====
pwgen
=====

A script for generating random passwords so simple that it shouldn't probably
even be a thing. But I find this useful in my day-to-day so maybe you would
too. Although, if you didn't come here specifically looking for this, you
probably shouldn't be using this. Here are a couple of alternatives probably
much better suited to your needs.

  - pwgen : https://github.com/jbernard/pwgen
  - apg : https://github.com/Distrotech/apg
  - makepasswd : https://github.com/khorben/makepasswd
  - also... https://xkcd.com/936

And (I'm guessing here) millions more. Heck, even this:

  $ head -c24 /dev/urandom | base64

gets the job done if you're really desperate. The only thing this repo may be
useful for, is if you're learning/teaching Python, in which case, hit me up if
you need any help.
