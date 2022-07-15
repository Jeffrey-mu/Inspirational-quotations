# Inspiration Documentation
## Introduction
This API generates quotes to motivate or inspire you!

## Overview
A GET request to this API returns data in the body as a JSON dump of the author and quote.

## Caching
The API uses a cache, which expires every hour so quotes do not get updated in this period.

## Usage
GET https://api.goprogram.ai/inspiration

The request takes no parameters, headers or query strings.

## Example
curl -X GET https://api.goprogram.ai/inspiration
Generates:
```json
{
  "quote": "You must do the thing you think you cannot do.",
  "author": "Eleanor Roosevelt"
}
```
