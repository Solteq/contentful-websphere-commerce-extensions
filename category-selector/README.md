# Installation

```
contentful space use <SPACE ID>
```

## First time install



```
contentful extension create --installation-parameters '{ "storeId": <your-store-id>, "imageServerBaseUrl": "https://<your-image-server>/",  "searchServerBaseUrl": "https://<your-search-server/", "fallbackImage": "https://<your-server>/path/to/img.png"  }'
```

## Updating after initial install

```
contentful extension update --force --installation-parameters '{ "storeId": <your-store-id>, "imageServerBaseUrl": "https://<your-image-server>/",  "searchServerBaseUrl": "https://<your-search-server/", "fallbackImage": "https://<your-server>/path/to/img.png"  }'

```


## Credits
Based on https://github.com/contentful/extensions/tree/master/samples/shopify


