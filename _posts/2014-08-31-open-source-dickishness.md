---

layout: post
title: "TJ Holowaychuk продал ExpressJS"
description: "А мейнтейнеры и не знали…"
keywords: ["JavaScript", "JS", "ExpressJS", "Node", "framework", "фреймворк", "TJ Holowaychuk"]
translation: 
  author: Eran Hammer
  title: "Open Source Dickishness"
  link: http://hueniverse.com/2014/07/30/open-source-dickishness/

---

![](/assets/articles-assets/expressjs.jpg)

{:.photo-author}
_фото: [jdhancock](https://www.flickr.com/photos/jdhancock/)_

Вчера, на удивление комьюнити ExpressJS, создатель фреймворка и мейнтейнер
фреймворка TJ Holowaychuk [продал][1] проект [компании StrongLoop][2],
коммерческому NodeJS-стартапу. Передача проекта [шокировала активных мейнтейнеров
проекта][3], которые занимались поддержкой фреймворка без участия автора с января.
Из-за небрежной передачи прав на репозиторий мейнтейнеры лишились возможности 
вносить изменения в проект (позднее права восстановили).

В [своем блоге][4] StrongLoop описали передачу проекта как огромный шаг в его
развитии. В этом посте продажа проекта называется «передачей спонсорского пакета»
_(transfer of sponsorship)_, но если все, что хотели сделать эти ребята — всего
лишь поддержка и помощь, то зачем потребовалось переносить проект?
Почему пост в блог, а не pull request был первым, что они сделали?

Допустимо ли так грубо нарушать основные принципы open source и забирать проект
у тех, кто честно занимался его поддержкой? Продать их права на open source
проекты не правильно, в отличии от, скажем торговых знаков, где это вполне
обычная практика.

Успех проектов с открытым исходным кодом не заслуга его создателя, 
а результат труда всех его контрибуторов и сообщества. Успех Express — это 
работа людей, которые участвовали в его разработке, а не одного человека,
даже если он [«отвечает за ~95%+ проекта»][5]

Когда TJ Holowaychuk потерял интерес к поддержке Express, он поступил правильно,
отдав другим его поддержку и развитие. В тот момент проект, фактически, перестал 
ему принадлежать, даже не смотря на то, что он продолжал храниться в его
GitHub-аккаунте. Это вполне обычная практика, когда проект поддерживают другие
разработчики.

Оставить проект под его оригинальным URL — хороший способ продолжить его
поддержку, отдавая почести автору. Но этот факт не может позволить автору,
молча, взять и забрать права назад, тем более с намерением продать проект
кому-либо. Не говоря уже о том, что Express уже имеет собственную 
[GitHub-организацию][6], готовую хранить проект у себя.

Что делает эту передачу проекта особенно печальной, так это тот факт, что
права создателя были переданы компании, которая напрямую занимается монетизацией
ExpressJS, продавая как профессиональные сервисы так и продукты, построенные на
этом фреймворке. Благодаря возможности влиять на Express и его сообщество, 
StrongLoop получает несправедливое преимущество перед другими компаниями,
которые предоставляют подобные сервисы. Так же это создает потенциальный конфликт
интересов между продвижением Express и их коммерческим фреймворком LoopBack
(который так же основан на Express).

Покупка проекта приносит пользу исключительно StrongLoop и TJ Holowaychuk,
доставляя неудобства тем людям, которые занимались развитием проекта — 
мейнтейнерам и его коммьюнити.

_От переводчика: [вот ответ TJ о сложившейся ситуации][7]_

[1]: https://github.com/strongloop/express/issues/2264#issuecomment-50567002
[2]: http://strongloop.com/strongblog/tj-holowaychuk-sponsorship-of-express/
[3]: https://github.com/strongloop/express/issues/2264#issuecomment-50474787
[4]: http://strongloop.com/strongblog/tj-holowaychuk-sponsorship-of-express/
[5]: https://twitter.com/tjholowaychuk/status/494294255448236032
[6]: https://github.com/expressjs
[7]: /2014/08/31/strongLoop-and-express/