### A URL Shortener Project using Go/fiber, Redis and Docker

#### The ShortenURL function 
- Implements Rate Limiting
- Check for Invalid URL
- Check for domain error
- Enforce https, ssl
- Shorten the URL

A post request to /api/v1
```
{
  "url": "The link you want to shorten",
  "short": "optional custom short"
}
```

#### The ResolveURL function
- Takes the shortened url and redirects to the destination link
