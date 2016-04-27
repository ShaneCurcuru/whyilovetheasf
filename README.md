# WhyILoveTheASF    
> Website about cool stuff at Apache.


## Todo: Post Options

All the post, require an image and maybe an author, the image are used in the cards and the autor used for the footer in the cards. For use the images and author, just add a new key in the post config, something like this:

    ---
    layout: post
    title:  "Welcome to jekyll-mdl"
    date:   2015-07-11 11:34:20
    categories: jekyll
    image: http://www.wchs4pets.org/wp-content/uploads/2015/03/cat_1-jpg.jpg
    author: Google Developers Group Managua
    ---

## Layout Configuration
You can setup 4 types of layout

- Fixed Nav + Simple Card Grid
- Fixed Nav + Highlight Post + Card Grid
- Drawer Nav + Simple Card Grid
- Drawer Nav + Highlight Post + Card Grid

For use this in the [_config.yml](https://github.com/gdg-managua/jekyll-mdl/blob/master/_config.yml) select the type of layout, rebuild the website and voilà :smile:


## License
Licensed under the Apache 2.0 license.

Forked from jekyll-mdl.
