# GitHub Pages Source

My GitHub Pages site is created with the Hugo static site generator.  This repo contains the code that renders that site.  Feel free to poke around and use it as inspiration for your own.

## Helpful Links

**Hugo Static Site Generator**  
[https://gohugo.io/](https://gohugo.io/)  

**Mainroad Theme**  
[https://github.com/Vimux/Mainroad/](https://github.com/Vimux/Mainroad/)

## Initial Commands

A few helpful commands to help you get started with Hugo:

|  Command  |  Description  |
|-----------|---------------|
| `npm -g hugo` | Install Hugo globally. |
| `hugo new site myblog` | Create a new site for your blog. |
| `hugo new posts/hola.md` | Create a new post. |
| `hugo server` | Lanch the site locally for testing. |
| `hugo` | Build the site into the `public` folder. |`

## Installing Themes

Unlike the Hugo docs, I **do not** recommend using Git submodules.  After cloning a theme into project I immediately remove the theme's `.git` folder:

```bash
cd ./myblog
git clone https://github.com/vimux/mainroad.git themes/mainroad
rm -rf ./themes/mainroad/.git
```


## Contact Info  

Feel free to reach out if I can help in any way.  

**Fred Lackey**  
[fred.lackey@gmail.com](mailto:fred.lackey@gmail.com)  
[http://fredlackey.com](http://fredlackey.com)  
