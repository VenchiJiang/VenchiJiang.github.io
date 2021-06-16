---
layout: post
title:  a post with github metadata
date: 2020-09-28 21:01:00
description: a quick run down on accessing github metadata.
---

A sample blog page that demonstrates the accessing of github meta data.

## What does Github-MetaData do?
* Propagates the site.github namespace with repository metadata
* Setting site variables : 
  * site.title
  * site.description
  * site.url
  * site.baseurl
* Accessing the metadata - duh.
* Generating edittable links.

## Additional Reading
* If you're recieving incorrect/missing data, you may need to perform a Github API<a href="https://github.com/jekyll/github-metadata/blob/master/docs/authentication.md"> authentication</a>.
* Go through this <a href="https://jekyll.github.io/github-metadata/" target="blank">README</a> for more details on the topic.
* <a href= "https://github.com/jekyll/github-metadata/blob/master/docs/site.github.md">This page</a> highlights all the feilds you can access with github-metadata.
<br />

## Example MetaData
* Host Name : {{ site.github.hostname }}
* URL : {{ site.github.url }}
* BaseURL : {{ site.github.baseurl }}
* Archived : {{ site.github.archived}}
* Contributors : 
{% for contributor in site.github.contributors %}
  * {{ contributor.login }}
{% endfor %}

#### Hipster list
<ul>
    <li>brunch</li>
    <li>fixie</li>
    <li>raybans</li>
    <li>messenger bag</li>
</ul>

Hoodie Thundercats retro, tote bag 8-bit Godard craft beer gastropub. Truffaut Tumblr taxidermy, raw denim Kickstarter sartorial dreamcatcher. Quinoa chambray slow-carb salvia readymade, bicycle rights 90's yr typewriter selfies letterpress cardigan vegan.

<hr>

Pug heirloom High Life vinyl swag, single-origin coffee four dollar toast taxidermy reprehenderit fap distillery master cleanse locavore. Est anim sapiente leggings Brooklyn ea. Thundercats locavore excepteur veniam eiusmod. Raw denim Truffaut Schlitz, migas sapiente Portland VHS twee Bushwick Marfa typewriter retro id keytar.

<blockquote>
    We do not grow absolutely, chronologically. We grow sometimes in one dimension, and not in another, unevenly. We grow partially. We are relative. We are mature in one realm, childish in another.
    —Anais Nin
</blockquote>

Fap aliqua qui, scenester pug Echo Park polaroid irony shabby chic ex cardigan church-key Odd Future accusamus. Blog stumptown sartorial squid, gastropub duis aesthetic Truffaut vero. Pinterest tilde twee, odio mumblecore jean shorts lumbersexual.
