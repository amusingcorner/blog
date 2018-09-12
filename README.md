### Creating new hugo site
- `mkdir amusingcorner`
- `hugo new site amusingcorner && cd amusingcorner`


### Multiple git accounts
Since this is a secret git account for my secret website. I will be using mutlple git accounts locally
Follow the link to understand how to setup multiple git accounts 
https://gist.github.com/jexchan/2351996
http://code.tutsplus.com/tutorials/quick-tip-how-to-work-with-github-and-multiple-accounts--net-22574


### Handling git submodules being used for hugo themes
https://stackoverflow.com/a/1032653

## Run hugo server
hugo server

## Build hugo site
hugo -t hugo-future-imperfect

## Pushing changes
git push --recurse-submodules=on-demand

## Publishing on Github pages
https://gohugo.io/hosting-and-deployment/hosting-on-github/

## Setting godaddy for github pages
https://hackernoon.com/how-to-set-up-godaddy-domain-with-github-pages-a9300366c7b