# Chambers of Chaos

This site is being built on YouTube, one week at a time. See all the videos up to date here: [How to build a professional website from start to finish](https://www.youtube.com/playlist?list=PLqGj3iMvMa4KQZUkRjfwMmTq_f1fbxerI)

Subscribe to [the channel](https://www.youtube.com/user/DevTipsForDesigners) to follow along as we develop this project step by step from the beginning.

## How to install/use

In order to get this super fantastic [Jekyll](http://jekyllrb.com) powered template for Artists follow this simple step:

* If you haven't got ruby installed on your computer, install it.
* Then run in your terminal `$ gem install jekyll`
* Move/`cd` to a folder, always in your terminal, in which you want to insert the *Artists-Theme*
* Run `git clone https://github.com/DevTips/Artists-Theme.git`
* Then `cd Artists-Theme`
* `jekyll serve --watch` or 'jekyll build --watch', optional parameter: '--force_polling'
* **DONE**

Isn't it fantastic?

Learn how to [use Jekyll on windows](http://jekyll-windows.juthilo.com/) (if that's your thing :)


//
Run Jekyll without errors:
No BOM allowed
If there are BOM header characters in your UTF-8-encoded files, Jekyll will break. Make sure there are none.

Set your encoding to UTF-8
Depending on the version of Ruby and/or Jekyll you’re using, your site’s content, and maybe other factors, you may need to make sure Jekyll will read your site’s source as UTF-8.

If you followed this guide step by step or if your versions match the ones in this guide, you shouldn’t need to use any of the following fixes.

Set encoding option
Since Jekyll v1.3.0, you can specify the encoding in your _config.yml:

encoding: utf-8
Change console encoding
Alternatively, you can change your command line tool’s encoding to UTF-8 by running the following command every time you open a new console window.

chcp 65001
Use subfolders
Jekyll cannot build or serve sites from certain system-reserved folders on Windows, like your user folder. Instead, it will output an error looking like this:

C:\Users\You>jekyll serve
Configuration file: C:\Users\You\_config.yml
            Source: C:\Users\You
       Destination: C:\Users\You\_site
      Generating...
jekyll 2.4.0 | Error: Permission denied - .
If you encounter such an error, move your site to a subdirectory (e.g., C:\Users\You\awesome-jekyll-site) and try again.

jekyll build
jekyll build --watch
jekyll build -w
jekyll serve
jekyll serve --watch
jekyll serve -w

Jekyll Tutorial: https://www.andrewmunsell.com/tutorials/jekyll-by-example/tutorial
//



## Credits

Example Site (Artist-Themes) Design and Tutorials by:
    Travis Neilson

_Code contributions via pull request:_
- [Riccardo Pasianotto](http://rkpasia.github.io)
- [cust0dian](https://github.com/cust0dian)
- [Dylan Spicker](https://github.com/ZDesign)
- [arielsafari](https://github.com/arielsafari)
- [bzerangue](https://github.com/bzerangue)
- [Brian Guerrero](https://github.com/brian-guerrero)
- [Vipul Bansal](https://github.com/vipsyvipul)
- [iiSa3](https://github.com/iiSa3)
- [Killua13](https://github.com/Killua13)
- [iMoritz](https://github.com/iMoritz)
- [jgrimshaw](https://github.com/jgrimshaw)
- [boodaah](https://github.com/boodaah)
- [Vadzim](https://github.com/meecrobe)
- [Eric Ellenbrook](https://github.com/ellenbrook)
- [rodrigofuentes](https://github.com/rodrigofuentes)
- [Jonathan](https://github.com/foohyfooh)
- [George](https://github.com/g3org3)
- [Anders Thuesen](https://github.com/ande765a)
- [beRoberto](https://github.com/beRoberto)
- [Sven Kube](https://github.com/SvenKube)

_A big thank you to these creators for contributing sample projects for the "work" section:_
- [Micael Butial](https://www.behance.net/gallery/14751131/-TYPO-International-Design-Talks)
- [Petras Nargėla](https://www.behance.net/gallery/16750837/Free-80-Crispy-Icons-in-PSD-AI-SVG-Webfont)
- [Sergey Valiukh](https://www.behance.net/gallery/13745729/Timeline-Page)
- [Ayoub Elred](https://www.behance.net/gallery/15812143/Flat-Mobile-UIUX-Concept-download)
- [Anton Skvortsov](https://www.behance.net/gallery/16483395/City-IN-website-concept)
- [Nick Zoutendijk](https://www.behance.net/gallery/13870569/Stripes-Co-Free-icon-Set)
- [Jonathan Quintin](https://www.behance.net/gallery/12748107/Weather-Dashboard-Global-Outlook-UIUX)
- [Jieyu Xiong](https://www.behance.net/gallery/15063575/Fresh-It-Up-App-Design)

- [Dylan Cole](https://dylancolestudio.com) (a.k.a. exsanguinatus on DeviantArt) for Mt. Doom image.
- [webtreats](https://www.flickr.com/people/webtreatsetc) for table-top (background) image.
- [Zita Banyai](https://zitabanyai.artstation.com/resume) (a.k.a. moonlight4ngel, a.k.a. moondustowl, a.k.a painted-leaf) for papyrus (scroll background) image.


![The Design](/assets/img/the_design.jpg)


_Artist Themes in the wild:_
- [limestudios](http://limestudios.net/)


---


This is a free Jekyll Theme that was developed in weekly episodes on the [DevTips YouTube channel](http://youtube.com/devtipsfordesigners).
