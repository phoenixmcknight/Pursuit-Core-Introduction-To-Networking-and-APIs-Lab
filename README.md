# Pursuit-Core-Introduction-To-Networking-and-APIs-Lab

# Part One

Status Code Scavenger Hunt!

Use Postman to find each of the following HTTP codes:


1. 200
1. 301
1. 400
1. 401
1. 403
1. 404
1. 418
1. 500


For each of the questions below, write:

1. The website which generated the HTTP status code
2. A description of what the status code means
3. If an app you were writing encountered this status code, what would you do (if anything) to resolve any issues?

200 : 
* https://dog.ceo/api/breeds/image/random 
*'200' is the standard response for a successful request 
* there isn't an issue to resolve 

301 :

400 :
* https://api.twitter.com/1.1/users/show.json
* '400' is the response when the server can not or will not process a request becasue of an error client-side. 
* 
403 : 
*https://fortnite-api.theapinetwork.com/store/get
*'403' is the response for when the page or resource you were trying to reach is absolutely forbidden for some reason.
* Contact system admin to determine why you aren't allowed access. 
404 : 
*https://www.google.com/maps/embed/v1/
*'404' is the response for when the requested resource can not be found. 
* A potential solution is checking to make sure the url is typed in correctly. 

For reference, see:

https://en.wikipedia.org/wiki/List_of_HTTP_status_codes (Links to an external site.)
https://http.cat


# Part Two

API Scavenger Hunt!

For each of the questions below, identify a website and search query that will give you the appropriate JSON.  Paste the url and the json below.  Googling the category + API will generally take you to where you need.  Ex. t

1. A random cat fact - https://catfact.ninja/fact
}
 "fact": "Julius Ceasar, Henri II, Charles XI, and Napoleon were all afraid of cats.",
    "length": 74
}

1. A list of 150 random users in English. -  https://api.github.com/search/users?q=repos:%3E12+followers:%3C1000&location:uk+language:python&page=1&per_page=150


"login": "xiaolonw",
            "id": 10133277,
            "node_id": "MDQ6VXNlcjEwMTMzMjc3",
            "avatar_url": "https://avatars2.githubusercontent.com/u/10133277?v=4",
            "gravatar_id": "",
            "url": "https://api.github.com/users/xiaolonw",
            "html_url": "https://github.com/xiaolonw",
            "followers_url": "https://api.github.com/users/xiaolonw/followers",
            "following_url": "https://api.github.com/users/xiaolonw/following{/other_user}",
            "gists_url": "https://api.github.com/users/xiaolonw/gists{/gist_id}",
            "starred_url": "https://api.github.com/users/xiaolonw/starred{/owner}{/repo}",
            "subscriptions_url": "https://api.github.com/users/xiaolonw/subscriptions",
            "organizations_url": "https://api.github.com/users/xiaolonw/orgs",
            "repos_url": "https://api.github.com/users/xiaolonw/repos",
            "events_url": "https://api.github.com/users/xiaolonw/events{/privacy}",
            "received_events_url": "https://api.github.com/users/xiaolonw/received_events",
            "type": "User",
            "site_admin": false,
            "score": 1.0
        },
1. The current stock price of Microsoft. (IEX API) - https://sandbox.iexapis.com/stable/stock/MSFT/quote?token=Tpk_bf7c800d40244b80b91c24dd593eb008
{
 "symbol": "MSFT", "companyName": "Microsoft Corp.", "primaryExchange": "NQDASA", "calculationPrice": "tops", "open": null, "openTime": null, "close": null, "closeTime": null, "high": null, "low": null, "latestPrice": 135.76, "latestSource": "IEX real time price", "latestTime": "2:35:20 PM", "latestUpdate": 1620478911019, "latestVolume": null, "iexRealtimePrice": 139.12, "iexRealtimeSize": 105, "iexLastUpdated": 1598936366045, "delayedPrice": null, "delayedPriceTime": null, "extendedPrice": null, "extendedChange": null, "extendedChangePercent": null, "extendedPriceTime": null, "previousClose": 138.15, "previousVolume": null, "change": 1.47, "changePercent": 0.0114, "volume": null, "iexMarketPercent": 0.02930655072116735, "iexVolume": 361161, "avgTotalVolume": 27029866, "iexBidPrice": 140.13, "iexBidSize": 104, "iexAskPrice": 142.55, "iexAskSize": 100, "marketCap": 1048437264765, "peRatio": 27.7, "week52High": 142.49, "week52Low": 96.73, "ytdChange": 0.331725547430799, "lastTradeTime": 1582365160802, "isUSMarketOpen": true
 }
1. The 5 year history of Apple stock prices (IEX API)
1. All the Swift language repos on Github with Pursuit in their name - https://api.github.com/search/repositories?q=pursuit+language:swift&sort=stars&order=desc

 {
            "id": 39978693,
            "node_id": "MDEwOlJlcG9zaXRvcnkzOTk3ODY5Mw==",
            "name": "swift-wisdom",
            "full_name": "IntrepidPursuits/swift-wisdom",
            "private": false,
            "owner": {
                "login": "IntrepidPursuits",
                "id": 2151424,
                "node_id": "MDEyOk9yZ2FuaXphdGlvbjIxNTE0MjQ=",
                "avatar_url": "https://avatars1.githubusercontent.com/u/2151424?v=4",
                "gravatar_id": "",
                "url": "https://api.github.com/users/IntrepidPursuits",
                "html_url": "https://github.com/IntrepidPursuits",
                "followers_url": "https://api.github.com/users/IntrepidPursuits/followers",
                "following_url": "https://api.github.com/users/IntrepidPursuits/following{/other_user}",
                "gists_url": "https://api.github.com/users/IntrepidPursuits/gists{/gist_id}",
                "starred_url": "https://api.github.com/users/IntrepidPursuits/starred{/owner}{/repo}",
                "subscriptions_url": "https://api.github.com/users/IntrepidPursuits/subscriptions",
                "organizations_url": "https://api.github.com/users/IntrepidPursuits/orgs",
                "repos_url": "https://api.github.com/users/IntrepidPursuits/repos",
                "events_url": "https://api.github.com/users/IntrepidPursuits/events{/privacy}",
                "received_events_url": "https://api.github.com/users/IntrepidPursuits/received_events",
                "type": "Organization",
                "site_admin": false
            }

1. A list of all Pokemon - https://pokeapi.co/api/v2/pokemon?offset=1&limit=964
{
            "name": "medicham",
            "url": "https://pokeapi.co/api/v2/pokemon/308/"
        }
1. A list of all items in Fortnite - https://fortnite-api.theapinetwork.com/items/list

1. A list of all Game of Thrones Episodes. - https://api.got.show/api/map/episodes
 {
 "totalNr": 31,
            "season": 4,
            "nr": 1,
            "name": "Two Swords",
            }
1. A list of all songs with "Love" in the title. -  http://ws.audioscrobbler.com/2.0/?method=track.search&track=Love&api_key=7e102a7a374864e194aab0b8543ccb45&format=json


1. All information about Petyr Baelish from the Game of Thrones books 
1. All the movies Leonardo Dicaprio has acted in -
