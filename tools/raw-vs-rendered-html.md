# Raw vs Rendered HTML

## What It Checks

This tool compares the initial HTML response with the content available after JavaScript renders the page.

## When To Use It

Use it when a JavaScript-heavy page works for visitors but may not expose content in the first HTML response.

## What The Results Mean

A large raw-vs-rendered gap means the browser sees more than the crawler may receive from the initial request.

That does not automatically mean the page cannot be indexed, but it is a strong signal to investigate crawler-readable HTML.

## Live Tool

https://prerenderbuddy.com/tools

