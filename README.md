# Robert Bamler Research Group Web page

Hey! This is the repository for our group webpage.

## Creating your own people page
To create a page for yourself in the people section, just create a markdown (.md) file in the _people folder, titled with your name. 
Additionally, add an image of yourself to the `assets/img` folder (try to keep it small and make it exactly square!!)
As a header in the markdown file, use the following: 

```
---
name: <your name>
title: <your name>
position: <Phd Student, Bachelor Student etc.>
layout: people
picture: /assets/img/your_img.png
research: <max 10-20 words>
# the following are optional
mail: <your mail address>
github: <your github link>
twitter: <your twitter
homepage: <your homepage>
googlescholar: <your google scholar>
---
```

Afterwards, you can write your own descriptions in markdown syntax (or alternatively html, both are parsed by jekyll). 
Make sure to include at least a header `## About` where you tell us something about yourself!
