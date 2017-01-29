# Cloudflare Sitemap Purger

Purges all the urls in a CloudFlare Zone's Cache by reading and parsing a sitemap.

### Usecase
I can't really purge everything in the zone, cos there are different sites running on the same url.
The usecase emerged for [fascinations.hannanali.tech](https://fascinations.hannanali.tech)
 where I wanted to purge the cache, after TravisCI automatically does a build.
 Purging everything in the cache wasn't possible, neither purging by tags (not an enterprise user),
 there is a build done, everytime something is pushed to the master, Cloudflare sitemap purger has
 proven to be very useful.