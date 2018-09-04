---
title: "Golang Http Test ~ Let's Type Less"
date: 2018-09-04T06:42:36+07:00
draft: false
---
-- Some says, **_Lazy Programmer makes Better Programmers_** --
some days ago I worked on testing http on golang. Golang has superb foundation
on Http Testing with It's ResponseRecorder component. To write the tests I used [Ginkgo](http://onsi.github.io/ginkgo/) and [Gomega](http://onsi.github.io/gomega/) two libraries
that makes writing BDD-styled test a breeze. But then when some test cases already written
I notice something. I do repetitive task, now it's become so boring. 

To code is to liberate, and doing thing repetitively means we get shackled into boringness. Yet Daenarys Targaryen the Mother of Dragons and the chain breaker won't be here to help us, we have to help ourselves..!!!. 

![Dracarys](https://media1.tenor.com/images/65f7c686781828e3121c463d8ee371e3/tenor.gif?itemid=7190780)

then again let's spell the mantra: **_Lazy Programmers makes Better Programmers_**. Let's makes the RequestRecorder boilerplate codes get organized and easier and less typier (_I know it's not a word_) to use. here is the snippet:
{{<gist zkrhm 8d97d9a798afcd02eb4f3360988f3c21 "httptest-codebootstrap.go" >}}

and here's how you can use it : 
{{<gist zkrhm 8d97d9a798afcd02eb4f3360988f3c21 "how_to_use.go" >}}

btw, I got the code marshal & unmarshal from an amazing app named QuickType. they makes json format - to language target conversion much more easier. Go check the tools [here](https://quicktype.io/)


