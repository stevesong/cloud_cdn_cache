# CDNs and Cloud Infrastructure

With the aim of creating a more comprehensive picture of global cloud and CDN infrastructure, I have collected data scraped from various service provider websites into CSV and GeoJSON format. So far, I have collected information from:

- [Cloudflare's Global Network](https://www.cloudflare.com/en-gb/network/)
- [Amazon's Local Zones](https://aws.amazon.com/about-aws/global-infrastructure/localzones/locations/)
- [Microsoft's Edge Locations](https://learn.microsoft.com/en-us/azure/frontdoor/edge-locations-by-region)
- [Google's Edge Locations](https://cloud.google.com/vpc/docs/edge-locations)
- [Fastly PoPs](https://www.fastly.com/network-map/)
- [Facebook (now Meta) Network Appliances](https://anuragbhatia.com/2022/07/networking/isp-column/facebook-cache-fna-updates-july-2022/)
- [Akamai](https://www.akamai.com/why-akamai)

For the above, I took the cache locations from the websites and geolocated them. Thus the map is only accurate to city level. The dates in the filenames indicate the last time the relevant website was checked.

For the Facebook Network Appliances, I have drawn on [Anurag Bhatia](https://anuragbhatia.com)'s very creative work in  work in locating them by the airport code in their names.

This is very much an exploration so comments and suggestions are extremely welcome.  Feel free to reach out to me [here](https://github.com/stevesong/cloud_cdn_cache/issues) or on social media [@stevesong@mastodon.cloud](https://mastodon.cloud/@stevesong) or [@stevesong](https://twitter.com/stevesong)

All data licensed under the [Open Data Commons Attribution License (ODC-By) v1.0](https://opendatacommons.org/licenses/by/1-0/)
