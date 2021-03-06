---
layout: relation
title: 'auxpass'
shortdef: 'passive auxiliary'
---

A passive auxiliary of a clause is a form of the [auxiliary verb](cs-pos/AUX) _быть_ “to be” used to construct the periphrastic passive voice (in the past or future tense, in the infinitive, imperative or conditional mood).

~~~ sdparse
Кеннеди был убит . \n Kennedy was killed .
auxpass(убит, был)
auxpass(killed, was)
~~~

~~~ sdparse
Кеннеди будет убит . \n Kennedy will-be killed .
auxpass(убит, будет)
auxpass(killed, will-be)
~~~

~~~ sdparse
Кеннеди не знал , что ему суждено быть убитым . \n Kennedy did-not-anticipate that his fate is to-be killed .
auxpass(убитым, быть)
auxpass(killed, to-be)
~~~
