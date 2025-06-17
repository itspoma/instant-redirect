# Instant Redirect

A lightweight service that redirects users based on URL patterns, with built-in Google Analytics tracking.

## Overview

Instant Redirect is a simple, client-side redirection service that transforms URL patterns into direct links. It's particularly useful for creating short, memorable links that redirect to complex URLs or for dynamically generating links based on IDs.

## How It Works

The service looks for patterns in the URL query string in the format `[[type-entity-id]]` and transforms them into direct links.

### Example Usage

```
https://your-domain.com/?https://example.com/[[runn-project-156102]]
```

This will redirect to:
```
https://example.com/156102
```

## Features

- Pattern-based URL transformation
- Google Analytics tracking for page views and redirects
- Visual loading indicator during redirect
- Error handling for invalid patterns
- Console logging for debugging
- Domain restriction for security (only allows specific domains)

## Deployment

Simply deploy the `index.html` file to any web server or hosting service that supports static files.

## Development

To modify or extend the service:

1. Clone this repository
2. Edit the `index.html` file
3. Test locally by opening the file in a browser
4. Deploy to your hosting service

## License

MIT
