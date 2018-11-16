# WebSphere Commerce extensions for the Contentful CMS


## Editors


### Product Selector

Allows picking a set of products from a WebSphere Commerce installation

Maps to an "JSON Object" field. Stores data as 
```
 [  
   { 
     partNumber: xyz,
     image: URL to image.
     name: name of product
   },
...
]
```

`image` and `name` are stored only to allow faster preview in Contentful.



### Category selector

Allows picking a set of categories from a WebSphere Commerce installation

Maps to a "JSON Object" field. Stores data as
```
  [
    {
      identifier: xyz
      image: Url to image
      name: name of category
    }
  ,...
  ]
```

`image` and `name` are stored to allow faster preview in Contentful.



### Marketing spot selector

Allows picking a marketing spot from a WebSphere Commerce installation

Maps to a `ShortText` field.


### Prerequisites

The extension runs in the users browser. 

This means, if the editor person can access a WebSphere Commerce authoring environment, you can point your search server url to that.

Otherwise point it to an externally mapped access to the live environments search server.


## License
MIT