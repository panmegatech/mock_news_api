# Mock News API

A simple **mock REST API** for news articles, created using [my-json-server](https://my-json-server.typicode.com/).  
This repository is designed for testing and educational purposes — ideal for small Flutter or web projects that need a fake API endpoint.

---

## Base URL

```bash
https://my-json-server.typicode.com/panmegatech/mock_news_api
````

---

## Endpoints
````
| Endpoint | Description |
|-----------|-------------|
| `/news` | Get all news articles |
| `/news/{id}` | Get a single news article by ID |
````
---

### Example

#### Get all news
```bash
GET https://my-json-server.typicode.com/panmegatech/mock_news_api/news
```

#### Get a specific news item
```bash
GET https://my-json-server.typicode.com/panmegatech/mock_news_api/news/1
```

#### Example Response
```bash
[
  {
    "id": 1,
    "title": "Flutter 4.0 Released with New Features",
    "description": "Flutter 4.0 improves performance and introduces full Material You support.",
    "imageUrl": "https://picsum.photos/400/200?random=1",
    "content": "Flutter 4.0 comes with major updates that improve cross-platform development..."
  }
]
```




