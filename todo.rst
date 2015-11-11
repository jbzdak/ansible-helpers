#. Add rate limiting to ssh connections, it has to be smart, because
   ansible is spawning ssh with connections --- so it will go over
   most limits. . .
#. Add an option for provision user to have password set-up (and then
   force him to provide it before sudo)
