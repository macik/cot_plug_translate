Localization of Cotonti Pligins
===============================

Simple guide how to translate (localize) of Cotonti plugin files hosted with GitHub.


HowTo
-----

This guide describes how to localize language files for Cotonti plugins hosted on GitHub.
It’s easy as 1-2-3. Just follow these steps:

Let’s assume we want to translate [`social_share`](https://github.com/macik/cot-social_share) plugin by [Macik](https://github.com/macik).

1. First of all, sign in GitHub (you [should be registered](https://github.com/)) and locate [`social_share`](https://github.com/macik/cot-social_share).

 Goto repository of source plugin, locate there __`lang`__ folder (path will be `cot-pluginname/plugins/plugin_name/lang/` or similar).
 
 Find English version of language file (with `en` mark in file name), or other country language file you can translate to your language. Open it with __«Raw»__ button on the panel. ([direct link](https://raw.github.com/macik/cot-social_share/master/plugins/social_share/lang/social_share.en.lang.php))

 You can see «raw» source text of file - just copy it to clipboard (in Windows you can press `Ctrl-A` to select all text, and `Ctrl-C` to copy it).

 Go back to __`lang`__ folder (with direct link or by pressing `←prev.page` button in your browser panel). Press __«+»__ sign button to fork repository and create new file. ([direct link](https://github.com/macik/cot-social_share/new/master/plugins/social_share/lang))

 Name it as  `plugin_name.##.lang.php`, where `plugin_name` is name of plugin, and `##` is 2-letter code for you language (see this file if you doubt).

 Paste english text from clipboard and start translating it. As you done press __«Propose New File»__ button. Name your commit as (for example) `Translation in Brazil` and press __«Send pull request»__. Thats all! 


 Now you can browse commit to download translation file - click `Files changed` → `View file @ …` button → right-click on `Raw` button to download source(click `Save As…`). 


 Place this file in `lang` folder of plugin on your site for use.


Now, as author of plugin merged you translation commit it will be automatically included in original plugin downloads for all users. Respect.



