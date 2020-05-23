# ORGANIZATION
### CSS GLOBAL
When CSS is added to DIVI or WP, add it directly or change things in theme's files so it won't look as "newbie" code when ctrl+I
<br/>
### ANIMATION
I've got the final result explained by schems, vids, draws. Free to myself to do the work the best way ( check the "CODE" part )
<br/>
### BACKUPS
Backup can be done with Updraft using dropbox, FTP or a lot of other things.<br/>
The best thing mixing usefull & security would be to be on a VPS and the server does an automatic backup every X days and store it on another server (FTP) only there to be a backup of everything.<br/>
This way, it'll be easy to make & reuse backup but also to encrypt everything coming from and going to the latter server.

<br/><br/><br/>
# 2.WORDPRESS
<br/>
### STICKY MENU
https://astucesdivi.com/menu-sticky-on-scroll-divi/<br/>
I cannot do anything until Lucie&Syl20 are OK about the style<br/>
Pretty easy to implement it, just have to play with some DIVI settings + add some JS evenlistener + styling with CSS
<br/>
### SEARCH BAR
https://www.elegantthemes.com/documentation/divi/search/<br/>
https://www.divi-community.fr/en/tutoriels-divi/creer-page-recherche-personnalisee-avec-theme-builder-divi/<br/>
DIVI search bar is enough for what we need to do on the website + We can place anywhere like in the middle of a webpage or in the header or in the footer<br/>
https://www.elegantthemes.com/blog/divi-resources/how-to-add-a-search-field-to-divis-secondary-menu<br/>
https://www.youtube.com/watch?v=ImUGrr6targ<br/>
https://divisoup.com/q19-replace-the-divi-search-button-with-an-icon/<br/>
We can also do it in pure code, we just need to inject the php code to get the search form and then play with some CSS so it looks like something ok<br/>
Now free to the designer to choose how he wants it, what would be the best between hardcoded & already-present things<br/>
<br/>
### CONTACT FORM
https://fr.wordpress.org/plugins/contact-form-7/<br/>
https://wpmarmite.com/contact-form-7/<br/>
Useless to do this the hardcoded way as we don't have enough time to do such a thing, so using CF7 is way more easier + the plugin is really good<br/>
Let them (L&S) make the design then I'll be able to implement it, or even let them make it by themselves if I explain it well ( sooo, let's document myself the best I can )<br/>
Don't need coding skill to add boxes as there is a builder already able to do such a thing<br/>
As for the design, I'll let the Designers do the works ( I suck at it )<br/>
<br/>
### MULTILINGUAGE
https://wp-ninja.fr/comment-ajouter-google-traduction-sur-wordpress/<br/>
Following this tutorial, you'll use GTranslate and you'll be able to translate the whole website using Google Translate. (drawbacks: some mispelling)<br/>
https://wordpress.org/plugins/weglot/<br/>
https://wordpress.org/plugins/translatepress-multilingual/<br/>
https://wordpress.org/plugins/polylang/<br/>
That is the best way to make a full translation of a website, using one of these plugins. The first one is known to be the "best" as it translates automatically + there is a manual translation manager. The last one is known to break the website so let's be aware of this one.<br/>
https://wordpress.com/support/domains/map-subdomain/<br/>
To do the multilingual website without using plugins, we'd have to do severals change in settings and map subdomains
Using subdomains and some programming skills, the website could detect what language is default on user's computer and then switch to /fr or /en or /es or /it etc. TLD, SUBS & Folders<br/>
https://litebreeze.com/software-development/multilingual-website-tld-vs-subfolder-vs-subdomain/#introduction-to-structuring-multilingual-content<br/>
This latter one is an explanation about what are the differences between those one<br/>
But it would be wayyyyyyy easier to do such a thing on a VPS than doing it on a damn WP stored on a host<br/>
Using a VPS, I just need to have multiple subfolders for each webpage & then append 3 lines to .htaccess and the work is done.<br/>
<br/>
### CLICKABLE NUMBERPHONE
https://www.markhendriksen.com/how-to-make-a-phone-number-clickable-in-divi/<br/>
To make a number phone clickable you just have to append "tel:" to the number phone using a href tag and the work is done.
Designer have then to choose the design for the clickable phone number + where they want to place it<br/>
<br/><br/>

# 3.CODE
<br/>
### BUBBLE ANIMATION
Will make this one to start with, as it's an easy one using little CSS & JS skill.<br/>
<br/>
### ANCHORS
When the website will be done, ask them what they exactly want as anchor, and do it + dev a little box where all anchor are linked so the browsing is smooth.<br/>
Here is a cool and smooth example<br/>
https://forum.manjaro.org/t/unrecognized-archive-format-pour-fichier-pkg-tar-zst/120547
<br/>
### PRELOADER
If website is way too big, we'll have to use a preloader. It can be done both using plugin and hardcode ( I could also mix these two as well )<br/>
 
<br/><br/>

# 4.LATER
<br/>
### SITEMAPS 
https://kinsta.com/fr/blog/sitemap-wordpress/<br/>
It's all about files like robots.txt & sitemaps.xml<br/>
There are free plugins around able to do the works but it can be done manually ( until the website is made of multiples links )
<br/>
### GOOGLE ADS
https://blog.hubspot.fr/marketing/guide-complet-google-ads<br/>
https://www.digitaweb.com/blog/configurer-campagne-adwords<br/>
Google Ads is pretty easy to configure and to understand, you only have to choose the right settings ( easy thing ) and then wait for people to click on it etc<br/>
Another thing that would team with Google Ads is SEO<br/>
<br/>
### SEO
https://fr.wikipedia.org/wiki/Search_engine_marketing<br/>
https://fr.wikipedia.org/wiki/Bombardement_Google<br/>
https://fr.wikipedia.org/wiki/%C3%89l%C3%A9ment_meta#Utilisation_dans_la_recherche_d'information<br/>
https://fr.wikipedia.org/wiki/Nofollow<br/>
https://fr.wikipedia.org/wiki/Social_media_optimization<br/>
https://fr.wikipedia.org/wiki/Spamdexing<br/>
https://fr.wikipedia.org/wiki/Netlinking<br/>
These are the core ways of optimizing the SEO, but be aware of Spamdexing, as Google could do some "blacklist" thing to a website doing so<br/>
https://astucesdivi.com/divi-seo-friendly/<br/>

### WEBSITE SPEED
https://gtmetrix.com/<br/>
https://www.youtube.com/watch?v=JZVaeJwp7Zs<br/>
It'll be a lot about PluginVScodeVStheme & how we optimize pictures and the website itself. It's something we'll have to look at every time we update it.<br/>
When updating somthing on the website, try the three ways and keep the most quicker one.<br/>

### RESPONSIVE
Everything should already be responsive thanks to WP & DIVI.<br/>
When the websit is done (or almost done), switch User-Agents and test the website for most of them and try finding some responsive issues (+ fix them)<br/>

### SOURCE CODE
https://stackoverflow.com/questions/14230411/how-to-hide-wordpress-details-from-view-source-code<br/>
Could be possible, but it's a pain to do such a thing on a host.<br/>
On a VPS, I could have played with .htaccess (again) + rename all files from wordpress + remove things that could help hacker's for Information Gathering<br/>

