---
layout: post
title:  "UkrOps дайджест #0010"
date:   2017-04-14 12:00:00 +0200
categories: news
---


Новости
-------
[Over The Air: Exploiting Broadcom’s Wi-Fi Stack](https://googleprojectzero.blogspot.com/2017/04/over-air-exploiting-broadcoms-wi-fi_4.html) - Тут такое дело! Оказывается, broadcom – решето, и потенциально уязвимы миллионы устройств. Ребята упоролись и отреверсинженерили все что можно было, в результате - нашли проблему. Apple вроде уже даже запилил фикс. 
[$PHP не нужен* ](https://habrahabr.ru/post/326284/) - ну, вот, как-бы ... Да.  
[Вышел graphite 1.0](https://graphite.readthedocs.io/en/latest/releases/1_0_0.html) — спустя миллион лет в разработке. Куча новых функций и оптимизация работы. 
[Вышла альфа prometheus](https://prometheus.io/blog/2017/04/10/promehteus-20-sneak-peak/) — ребята разрботали новый движек и вообще. 
[Вышел nginx 1.12 stable](https://www.nginx.com/blog/nginx-1-12-1-13-released/) — все улучшения из 1.11 теперь в стабильной ветке. 
[Spotify и DNS](https://labs.spotify.com/2017/03/31/spotifys-lovehate-relationship-with-dns/) — очень прикольная статья о том как в spotify готовят DNS. 

Процессы
--------
[IT Automation Best Practices for Network Engineers and Architects](https://thenewstack.io/automation-best-practices-network-engineers-architects) - довольно стандартные вещи, описанные умными словами. В общем, повторение - мать учения. 


Мнения
------
[Docker Image Vulnerability Research](https://www.federacy.com/docker_image_vulnerabilities) - ребята поресерчили, и решили что четверть всех Docker имеджей имеют уязвимости. Ну ок. 


Туториалы
---------
[Sockets in a Bind: Troubleshooting Port Exhaustion in Heroku's Routing Layer](https://engineering.heroku.com/blogs/2017-03-30-sockets-in-a-bind/) - совсем недавно у Heroku немного поламался роутинг, точнее возник большой латенси. Ребята решили эту проблему, и делятся опытом для всех - как не попасть в подобный просак. Статья писали 2 инженера из SRE team. 
[Preventing cross-site attacks using same-site cookies](https://blogs.dropbox.com/tech/2017/03/preventing-cross-site-attacks-using-same-site-cookies/?utm_source=webopsweekly) - как Dropbox хендлит CSRF атаки, и как сделать это в вашем продукте. 
[Mastering HTTP Caching - from request to response and everything](https://blog.fortrabbit.com/mastering-http-caching) - очень хороший Deep dive в кеширование, теория смешанная с реальными примерами. Интересно!


Тулзы
-----
[Lsyncd (Live Syncing Daemon) synchronizes local directories with remote targets](https://github.com/axkibe/lsyncd) - штуковина на основе rsync, которая умеет трекать inotify и fsevents, для того чтобы очень быстро синкать изменения. 
[BCC - Dynamic Tracing Tools for Linux](https://iovisor.github.io/bcc/) - очень мощный инструмент для трейса и дебага. Был прорекламирован @ctrlok на DevOps митапе. 

Linux
-----
[Ubuntu on AWS gets serious performance boost with AWS-tuned kernel](https://insights.ubuntu.com/2017/04/05/ubuntu-on-aws-gets-serious-performance-boost-with-aws-tuned-kernel) - AWS и Canonical скооперировались, и запилили натюненное ядро. Теперь у Ubuntu в ES2 самый длинный. 
[BPF - the forgotten bytecode](https://blog.cloudflare.com/bpf-the-forgotten-bytecode/) - Инженер из Cloudflare в печали из-за того, что все используют tcpdump, но никто не понимает как он работает внутри. Типуля опысывает как происходит magic, и на примере показывает - как они это юзают у себя в компании. 


Падения
-------
[Update on the April 5th, 2017 Outage](https://www.digitalocean.com/company/blog/update-on-the-april-5th-2017-outage/) - Digitalocean дропнул себе базу, и потом восстановил за пару часов. Интересно, наверное они перехантили к себе чувака из Gitlab? 


Цитаты великих
--------------
[Swift и Raid part 1](https://ukrops.slack.com/archives/C0VFW0Q6N/p1491281636653073), [Swift и Raid part 2](https://ukrops.slack.com/archives/C0VFW0Q6N/p1491282029693972), [Swift и Raid part 3](https://ukrops.slack.com/archives/C0VFW0Q6N/p1491282559749896), [Swift и Raid part 4](https://ukrops.slack.com/archives/C0VFW0Q6N/p1491282962791005) - годнота от @ikarpov, размышления на тему - что такое RAID и Swift, какие задачи они решают, и почему нельзя пихать очень много дисков в сервер. 


Шутки юмора
-----------
[Unikernel для php](https://github.com/tfjmp/php2uni) — они серьезно. 

oh cool, looks like Norton Commander is adding stories
![oh cool, looks like Norton Commander is adding stories](https://pbs.twimg.com/media/C8GivSWUwAA-H64.jpg)

[Debugging in production](https://video.twimg.com/tweet_video/C8FlmhtXgAEXFzs.mp4)

Новые видео из Epam: [оригинал](https://www.youtube.com/watch?v=H8aoBvOnK3U), [митинг](https://coub.com/view/t768w), [тает лед](http://coub.com/view/t771w)

![как поставить Gentoo](https://pp.userapi.com/c639324/v639324968/14451/rjTeikEZ8oI.jpg)
