# Rocket League Modding Wiki
This is still a WIP

# How to help ?
Simply upload or create a `.md` (`Markdown`) file in a folder.

Github let you create and edit `.md` files directly here.
To edit, there's an :pencil2: icon at the top right of a file page.
To create, there's a Create new file button at the top right when you're in a folder. You can create a folder by specifying it like:
`myfolder/myfile.md`

:warning: Please, try to respect the organization of the folders and create only `.md` files in the `pages` folder.


The file must start with this following header:
```
---
layout: default
title: Your Page Title
---
```

Then, add the url and title of this page in the `navigation.yml` file in the `_data` folder.

# How to make awesome pages ?
Github pages like ours use `Jekyll` to convert `.md` files into `.html`.
`Jekyll` use [Liquid](https://shopify.github.io/liquid/basics/introduction/) as templating language.
The syntax higlither used is [rouge](http://rouge.jneen.net/). 
The best way to learn is to inspire yourself from the already existing files.
