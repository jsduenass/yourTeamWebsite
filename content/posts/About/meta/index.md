---
title: "About the site"
date: 2021-05-19
description: personal notes and things related to the creation of the website
menu:
    sidebar:
        name: "About the site"
        identifier: meta
        parent: about
        weight: 1
        hero: hero.jpeg
---



The __[about section](/#about)__  holds a formal presentation of who I am. This however is a more lay back version where I intend to explore and also document different experiences.

## What I am currently interested in

* Computers
* Organizations
* Information
* Robots
* Cybernetics


## How do you justify your existence? 
This is a phrase that has stuck with me since the first time I read it in _The Tales of the Black Widowers_ by Isaac Asimov. Asimov is one of my favorite authors. He encapsulates a genuine wonder for the world and all what is around him. Through the lense of science fiction he builds a reflection of our own world with little sprinkles of speculation here and there to make something that feels foreign and yet very familiar. So  my way of answering this question would be.

> The world is a fascinating place, but we only get to live inside the boundary of what we know therefore I justify my existence by expanding this horizon to the farthest I can, and be amazed and amused by what there is out there.



## Building this website
Let's start from the beginning, I been thinking about writing for a long time but have struggled to do it for any meaningful length of time and keep up with it. I don't know when you are reading this but 2020/2021 have been period defined by a global pandemic which caused a rapid adoption of digital technologies. The times are changing so adapting to this new world with a bigger digital presence is a must.

That is why I start this project. If you want to get started creating a website of your own there a many alternatives, actually, too many. So many that it can become overwhelming. If you are wondering how this website in particular is made I used [HUGO](https://gohugo.io/) a static website builder based on ```go```, HUGO works via __themes__ to get a particular feel and aestethic I used the [hugo toha theme](https://hugo-toha.github.io) and ```fork``` a exemplary [git repository](https://github.com/hugo-toha/hugo-toha.github.io) which holds a generic site.  

> Spoilers: the template supports multilingual the forked example was in Bengali (বাংলা) 🇧🇩. 

This is not my first trying HUGO,  a while back I tried using it with a different template. In the end I didn't feel very confortable using it because my lack of experience but now trying it again, it feels a bit easier do to the fact that I have already tried it and become more familiar with the tool means I had already overcome some roadblocks and had to faceoff a new set of challenges. 

Starting a new project may be hard, you would find roadblocks that stop you right in your tracks, you might quit but even then it is not a waste of time if you ever return you no longer start from zero and bit by bit you get to advance. 


If you have gone this far I really appreciate it and hope you find the rest of the content in this posts just as interesting if not even more. Please reach out and share those projects you are or have worked on where you have encounter roadblocks I would enjoy to hear your stories.

## Migrate this website 2024
> The only constant is change itself

So ... the time has come and I have been putting this off I don't write much here this blog is just a compilations of list I find interesting that I up from time to time. But after a couple of failed deployments I decided it was time to do something. It was actually not the best time as I am currently quite busy, but something I have noticed is that I tend to focus better when it is the worst time, the most unconfortable and most odd to work. 4 years and a pandemic have pass Since starting this. I had encouter a small failure in deployment before which lead to my very small contribution to open source. Update the ubuntu version in the github action.

In the begining I forked the Toha's example page so my first instict was trying to merge the upstream to my repo. Despite the sporadic incursions with software development and programming this years have not translate in 4 years of expirience and the of multiple languages, frameworks, etc. I do feel more confortable with git and have learned a trick or two. branches no longer scare me. I merge the two repos but there was an issue when build the website while looking in the documentation trying to solve the issue i found the really helpful [Migration guide](https://toha-guides.netlify.app/posts/update-v3-to-v4/) and it worked pretty well I build the website locally and everything seems to be working pretty well. 

Now  for deploying here is my plan. 
- I should move my changes to source. 
- That however that is going to override the main branch with the web page so lets how that goes.
- After as sucessful build it would be worth transitioning to the new deplo workflow. 

How many commit is this going to take? testing github action is kind of a pain as you have to do a lot of commits lets start the count

> failed doply commits counter :1

After a first failed attemp lets change to the latest github actions

`
git checkout  upstream_main .\.github\
`

<p align = "center" >
<a href="mailto:jsduenass@unal.edu.co">
    <i class="fas fa-envelope fa-4x"style = "vertical-align:top; margin:4px"></i>
<a/>

<a href="https://github.com/jsduenass">
    <i class="fab fa-github fa-4x" style = "vertical-align:top; margin:4px"></i>
<a/>

<a href="https://www.linkedin.com/in/jsduenass/">
    <i class="fab fa-linkedin-in fa-4x" style = "vertical-align:top; margin:4px"></i>
<a/>

<a href="https://twitter.com/jsduenass">
    <i class="fab fa-twitter fa-4x"style = "vertical-align:top; margin:4px"></i>
<a/>

<p/>