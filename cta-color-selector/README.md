# Installation

```
contentful space use <SPACE ID>
```

## First time install

NOTE: Color names "primaryX" must match color names from sq-color-selector

```
 contentful extension create --installation-parameters '{ "primaryColors": "primary1|#d0bc81;primary2|#2f5246;primary3|#0090d2;primary9|#f3f3f7", "secondaryColors": ""  }' --environment-id int-test --space-id 7xsa2768nkz0 --mt $CONTENTFUL_XLBYG_ADM 
```

## Updating after initial install

```
 contentful extension update --force  --installation-parameters '{ "primaryColors": "primary1|#d0bc81;primary2|#2f5246;primary3|#0090d2;primary9|#f3f3f7", "secondaryColors": ""  }' --environment-id int-test --space-id 7xsa2768nkz0 --mt $CONTENTFUL_XLBYG_ADM 

```


## Credits
Based on https://github.com/contentful/extensions/tree/master/samples/shopify


