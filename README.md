# funky_scripts



This repo will collect interesting scripts I create on my way through internet technologies

#### google_search_to_wordcloud

This script will generate a wordcloud out of all your google searches you've ever done on your machine. 

Navigate to you Chrome/Chromium installation -> 
`cd /home/YOURUSERNAME/.config/chromium/Default`
(linux)

Install linuxbrew if youre under linux: 

`ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Linuxbrew/install/master/install)"`

Install kumo: 

`brew install https://raw.githubusercontent.com/kennycason/kumo/master/script/kumo.rb`

Change the USERNAME to yours. Change the wordcount parameter or remove it, if you want to have all words in the cloud.
Big thanks to my friend @kennycason writing this nice Java Wordcloud generator.

The database is locked if your browser is running. Close it before you start the script.

More scripts will follow. . ;)
