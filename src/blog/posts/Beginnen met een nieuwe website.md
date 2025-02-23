---
layout: layouts/post.njk
title: Beginnen met een nieuwe website
description: Openings blogpost
date: 2025-02-23
---
Zo, dit is de eerste blogpost op mijn nieuwe website.

Ik heb de website lokaal op mijn laptop gebowud met Eleventy.
En ik vond Minimal 11ty Starter een mooi en overzichtelijk thema voor de lay-out van deze website.

In een kwartiertje was de website lokaal op mijn eigen linux laptop up-and running.
<div><p><br><br>

```
(base) michiel@zandbelt:~$ git clone https://github.com/tomreinert/minimal-11ty-tailwind-starter.git
Cloning into 'minimal-11ty-tailwind-starter'...
remote: Enumerating objects: 375, done.
remote: Counting objects: 100% (62/62), done.
remote: Compressing objects: 100% (30/30), done.
remote: Total 375 (delta 35), reused 55 (delta 32), pack-reused 313 (from 1)
Receiving objects: 100% (375/375), 444.90 KiB | 6.18 MiB/s, done.
Resolving deltas: 100% (183/183), done.
(base) michiel@zandbelt:~$ cd minimal-11ty-tailwind-starter
(base) michiel@zandbelt:~/minimal-11ty-tailwind-starter$ npm install
(base) michiel@zandbelt:~/minimal-11ty-tailwind-starter$ npm run serve
```

<p><br>
en in je webbrowser het resultaat bekijken op https://localhost:8080/<br><br>
om je lokale website weg te schrijven naar een fodler die je kan uplaoden naar een online server (en die de naam _site krijgt) geef je in:<br>

```
(base) michiel@zandbelt:~/minimal-11ty-tailwind-starter$ npm run build
```

<br>



