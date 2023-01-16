---
title: Curriculum Vitae
feature_text: |
  All About Me
feature_image: "https://picsum.photos/2560/600?image=873"
excerpt: "Curriculum Vitae"
aside: false
---

{% include file.html link="/assets/Katrina_Liu_CV.pdf" height="600"%}

<div hidden>

#### Education
###### Harvard Medical School
Master of Biomedical Informatics, Aug. 2022-Now
###### Carnegie Mellon University
B.S. in Computer Science with Univerisity Honors, Aug. 2018-May. 2022\ 
<small>Minor in Mathematical Science, Computational Biology</small>\
<small>GPA: 3.86/4.0</small>

#### Honors
###### Dean's List with High Honors, Carnegie Mellon University
2018 Fall, 2019 Spring, 2020 Fall-2022 Spring
###### Dean's List, Carnegie Mellon University
2019 Fall

#### Research Experience
###### [Gehlenborg Lab](http://gehlenborglab.org/), Harvard Medical School
Graduate Research Assistant, Sep. 2022-Now\
<small>Supervisor: Dr. Nils Gehlenborg</small>
###### [Mohimani Lab](http://mohimanilab.cbd.cmu.edu/), Carnegie Mellon University
Undergraduate Research Assistant, Feb. 2021-Now\
<small>Supervisor: Dr. Hosein Mohimani</small>

###### Acuity Diagnostics
Machine Learning Research Assistant, Jun. 2022-Sep. 2022\
<small>Supervisor: Dr. Yongxin Zhao</small>
###### Summer Undergraduate Research Fellowship, Carnegie Mellon University
May. 2021-May.2022\
<small>Supervisor: Dr. Hosein Mohimani</small>
###### Summer Experience for Mathematical Science, Carnegie Mellon University
Jun. 2020-Aug. 2020\
<small>Supervisor: Dr. Kaave Hosseini</small>


#### Research-Based Project
###### Analysis of TCGA-MESO Samples Based on Mutation Variants and Gene Expression
Harvard Medical School
<small>Oct. 2022</small>

###### Predicting Biological Process Membership of Proteins from Protein-Protein Interaction Using Latent Mixed Membership Model
May 2022

###### Comparison of Active Learning and Traditional Supervised Classification Methods on High-Volume Cancer Gene Expression Data
May 2022

###### Comparison of TAD Callers for Structural Analysis of Cancer and Normal Cells
Dec. 2021

###### Correlation between SARS-CoV-2 Spike Protein Sequences and Structures
May 2021

#### Software-Based Project
###### Database Management System
Dec. 2021

###### Indeed for Labs
Dec. 2021

###### Consumer-to-Consumer eCommerce Platform
May 2021

###### Covid Analysis Framework
Apr. 2021
{% include video.html id="ek9Ppk304EY" title="Covid Analysis Framework" %}

###### Plant Pycoon
May 2019
{% include video.html id="Uxw2offyr1U" title="Plant Pycoon" %}
#### Work Experience
###### Teaching Assistant, Carnegie Mellon University
Aug. 2021-May 2022

###### Grader, Carnegie Mellon University
Aug. 2020-Dec. 2020

###### Peer Tutor, Carnegie Mellon University
May. 2020-. 2020

###### Teaching Assistant, Carnegie Mellon University
Aug. 2019-Dec.2019

###### Software Engineer Intern, Sina Corp
Jun. 2019-Aug. 2019

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

<small>A small element</small>

[A link](https://david.darn.es "A link")

Lorem ipsum dolor sit amet, consectetur adip* isicing elit, sed do eiusmod *tempor incididunt ut labore et dolore magna aliqua.

Duis aute irure dolor in [A link](https://david.darn.es "A link") reprehenderit in voluptate velit esse cillum **bold text** dolore eu fugiat nulla pariatur. Excepteur span element sint occaecat cupidatat non proident, sunt _italicised text_ in culpa qui officia deserunt mollit anim id `some code` est laborum.

* An item
* An item
* An item
* An item
* An item

1. Item one
2. Item two
3. Item three
4. Item four
5. Item five

> A simple blockquote

Some HTML...

``` html
<blockquote cite="http://www.imdb.com/title/tt0284978/quotes/qt1375101">
  <p>You planning a vacation, Mr. Sullivan?</p>
  <footer>
    <a href="http://www.imdb.com/title/tt0284978/quotes/qt1375101">Sunways Security Guard</a>
  </footer>
</blockquote>
```

...CSS...

``` css
blockquote {
  text-align: center;
  font-weight: bold;
}
blockquote footer {
  font-size: .8rem;
}
```

...and JavaScript

``` js
const blockquote = document.querySelector("blockquote")
const bolden = (keyString, string) =>
  string.replace(new RegExp(keyString, 'g'), '<strong>'+keyString+'</strong>')

blockquote.innerHTML = bolden("Mr. Sullivan", blockquote.innerHTML)
```

`Single line of code`

## HTML Includes

### Contact form

{% include site-form.html %}

``` html
{% raw %}{% include site-form.html %}{% endraw %}
```

### Demo map embed

{% include map.html id="1UT-2Z-Vg_MG_TrS5X2p8SthsJhc" title="Coffee shop map" %}

``` html
{% raw %}{% include map.html id="XXXXXX" title="Coffee shop map" %}{% endraw %}
```

### Button include

{% include button.html text="A button" link="https://david.darn.es" %}

{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}

``` html
{% raw %}{% include button.html text="A button" link="https://david.darn.es" %}
{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}{% endraw %}
```

### Icon include

{% include icon.html id="twitter" title="twitter" %} [{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes)

``` html
{% raw %}{% include icon.html id="twitter" title="twitter" %}
[{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes){% endraw %}
```

### Video include

{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}

``` html
{% raw %}{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}{% endraw %}
```


### Image includes

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}

``` html
{% raw %}{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}{% endraw %}
```
</div>
