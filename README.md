# Casper for LaurentStudio

[Live Demo](http://blog.howardgz.com)

Personal theme based on Casper, the default theme for [Ghost](http://github.com/tryghost/ghost/), with following features:

1. Personal [Duoshuo](http://duoshuo.com) comment system
2. Personal [Umeng](http://www.umeng.com) traffic analysis system
3. Some CSS changes

## How to use this theme

1. Fork this repository, 'git clone' it to local.
2. Edit codes (see next part in detail)
3. Commit and sync ur changes
4. Connect to ur remote repository, 'cd BLABLA/content/themes', and 'git clone' ur repository.
5. Restart app
6. Select this theme in /ghost/general/
7. Refresh your blog and enjoy!

## Edit codes

1. Replace the id in post.hbs (if you use Duoshuo), or replace them with other codes if u decide to use another comment system (like Disqus).
    1. Open post.hbs
    2. Find 'var duoshuoQuery = {short_name:"lurentstudio"};' and replace 'lurentstudio' with ur own id.
2. Replace the Umeng traffic analysis codes with ur own ones, or delete them if u don't need it.
    1. Open navigation.hbs in folder /partials.
    2. Find '<div class="traffic">...</div>', put ur codes in the div, or delete the div.
3. Change the name and version in package.json as you wish.
4. Replace the '.ico' file under folder /assets with ur own one.

## License

Released under the MIT License.
