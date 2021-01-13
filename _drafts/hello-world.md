---
layout: post
categories: []
title: Hello World
author: Editorial team
image: "/assets/images/eqkimwsxeaadwr0.jpeg"

---
* @acannon828, the protocol necessary depends on how you're connecting to git. The example provided assumes you are using the git protocol. The [git book](http://git-scm.com/book/en/Git-on-the-Server-The-Protocols) explains various protocols supported by git. – [kahowell](https://stackoverflow.com/users/1881136/kahowell "18,270 reputation") [Sep 26 '14 at 0:57](https://stackoverflow.com/questions/16330404/git-how-to-remove-remote-origin-from-git-repo#comment40810090_16330439)
* 2

  This is the correct answer, there is some confusion caused by the phrasing of the title and the question itself. – [Ian Lewis](https://stackoverflow.com/users/217696/ian-lewis "1,261 reputation") [Oct 22 '14 at 15:27](https://stackoverflow.com/questions/16330404/git-how-to-remove-remote-origin-from-git-repo#comment41652367_16330439)
* 3

  If you use Bitbucket instead of github you will delete the first "git://" part and directly write git@bitbucket.org:yourusername/reponame.git and of course change the place holders : "yourusername" and "reponame" with yours. – [Recomer](https://stackoverflow.com/users/4282841/recomer "160 reputation") [Feb 6 '16 at 8:32](https://stackoverflow.com/questions/16330404/git-how-to-remove-remote-origin-from-git-repo#comment58192162_16330439)