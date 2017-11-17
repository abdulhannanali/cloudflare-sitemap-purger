# Cloudflare Sitemap Purger

[![Greenkeeper badge](https://badges.greenkeeper.io/abdulhannanali/cloudflare-sitemap-purger.svg)](https://greenkeeper.io/)

Purges all the urls in a CloudFlare Zone's Cache by reading and parsing a sitemap.

### Usecase
I can't really purge everything in a cloudflare zone, cos there are different projects running on the same zone,
and the build for one of the project, doesn't mean other project should be purged too.
The usecase emerged for [fascinations.hannanali.tech](https://fascinations.hannanali.tech)
 where I wanted to purge the cache, after TravisCI automatically does a build.
 Purging everything in the cache wasn't possible, neither purging by tags (not an enterprise user).
 There is a build done, everytime something is pushed to the master, Cloudflare sitemap purger has
 proven to be very useful in purging the cache at those times for me :heart: