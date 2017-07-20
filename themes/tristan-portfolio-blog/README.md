# Tristan Portfolio Blog

Theme for [Hexo](https://hexo.io/) powered portfolio and blog. Built for responsiveness

## Configuration
Be sure to set up your main Hexo config file first to set all header information

In the theme configuration file you can set other variables such as keywords (comma separated), exterior links, about text, contact form email, disqus ID and google analytics id.

### Index
Most of this is hard coded for now in the 'index.ejs' file. Graphics are all SVG so I can change color via CSS

### Contact Page
To set up the contact page, in the cmd prompt type `hexo generate page "Contact"` then open the 'index.md' file under 'source > contact.' In the scaffolds, add in `layout: contact` to choose the correct layout file for the page, then if you wish to add a subtile you can also add `subtitle: Your subtitle text` to the scaffolds as well.

### Portfolio page
Similar to the contact page, in the cmd prompt type `hexo generate page "Portfolio"` then open the 'index.md' file under 'source > portfoilio.' In the scaffolds, add in `layout: portfolio' to choose the correct layout fild for the page, then if you wish to add a subtitle you can also add `subtitle: Your subtitle text` to the scaffolds as well. For the moment, most of the portfolio page is hard coded into the theme in the 'portfolio.ejs' file in the 'layout' folder. You can customize it as you wish, look for updates in the future.

## Further Customization
If you want to change styles, I have built this theme with [SASS](http://sass-lang.com/) and you'll find all the code under 'source > _scss' which you'll need a preprocessor to compile.

## Special Thanks
- [Disqus](https://disqus.com/) - Comments engine for the site
- [Font Awesome](http://fontawesome.io/) - for all the icons
- [Vecteezy](https://www.vecteezy.com/vector-art/106872-free-vector-tree-tops) - Trees in the header
- [Eucalyp at the Noun Project](https://thenounproject.com/search/?q=pcb&i=1116666) - Circuit SVG on the home page
- [Iconfinder](https://www.iconfinder.com) - For the rest of the icons and graphics
- [Formspree](https://formspree.io/) - Handles the contact for
- [Animate on Scroll Library](http://michalsnik.github.io/aos/ "AOS Github") - Animations on several pages
- [Koala](http://koala-app.com/) - Preprocessor for compiling [SASS](http://sass-lang.com/) stylesheets