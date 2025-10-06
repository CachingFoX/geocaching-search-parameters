# Geocaching Search Parameters

## Base URL
`https://www.geocaching.com/play/results?<parameters>` - Webpage

`https://www.geocaching.com/_next/data/release-20251002.1.2446/en/play/results.json?nfb=CachingFoX&sa=1&sort=placeDate` - JSON for a webpage

`https://www.geocaching.com/api/proxy/web/search/v2?nfb=CachingFoX&sa=1&sort=placeDate` - JSON

## Parameter list

* placeDate
* asc
* skip
* take
  


## Parameter "sort"

### Values
* `geocacheName`
* `distance`
* `favoritePoint`
* `containerSize`
* `difficulty`
* `terrain`
* `trackableCount`
* `foundDate`
* `placeDate`

## Parameter "asc"
This parameter controls the order of the sorting.

### Values
* `false` - Results are listed descending
* `true` - Results are listed ascending

## Parameter "skip"
`skip=<number>`

## Parameter "take"
`take=<number>`

### Notes
Doesn't work with the web page.

## Parameter "Archived"
With the parameter `sa`...
This parameter is used to show the found caches of a profile and not avaiable in the filter settings of the search page.

### Values
* 0: doesn't show archived caches
* 1: include archived caches

### Notes
The usage of the parameter is limited and only works in combination with `found by (fb)` parameter.

### Examples
* [https://www.geocaching.com/play/results?fb=CachingFoX&sa=0](https://www.geocaching.com/play/results?fb=CachingFoX&sa=0)
* [https://www.geocaching.com/play/results?fb=CachingFoX&sa=1](https://www.geocaching.com/play/results?fb=CachingFoX&sa=1)

# Typeahead

`https://www.geocaching.com/api/proxy/web/search/v2/typeahead?query=phoenix`

# Geocache

`https://www.geocaching.com/api/proxy/web/search/geocachepreview/GC640PF`

