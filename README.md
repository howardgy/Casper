# Casper for LaurentStudio

[Live Demo](http://blog.)

Personal theme based on Casper, the default theme for [Ghost](http://github.com/tryghost/ghost/), with following features:

1. [Duoshuo](http://duoshuo.com) personal comment system
2. Some CSS changes

## How to use this theme

1. Fork this repository, 'git clone' it to local.
2. Edit codes (see next part in detail)
3. Commit and sync ur changes
4. Connect to ur remote repository, 'cd BLABLA/content/themes', and 'git clone' ur repository.
5. Restart app
6. Select this theme in /ghost/general/
7. Refresh your blog and enjoy!

## Edit codes

1. Change the parameters in post.hbs (if you use Duoshuo), or replace them with other codes (like Disqus)
    1. Open post.hbs
    2. Find 'var duoshuoQuery = {short_name:"lurentstudio"};' and replace 'lurentstudio' with ur own id.
2. Change the name and version in package.json as you wish.

## Copyright & License

Copyright (c) 2013-2016 Ghost Foundation - Released under the MIT License.
