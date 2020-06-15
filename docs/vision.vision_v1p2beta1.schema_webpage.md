<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p2beta1](./vision.vision_v1p2beta1.md) &gt; [Schema$WebPage](./vision.vision_v1p2beta1.schema_webpage.md)

## vision\_v1p2beta1.Schema$WebPage interface

Metadata for web pages.

<b>Signature:</b>

```typescript
export interface Schema$WebPage 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [fullMatchingImages](./vision.vision_v1p2beta1.schema_webpage.fullmatchingimages.md) | [Schema$WebImage](./vision.vision_v1p2beta1.schema_webimage.md)<!-- -->\[\] | Fully matching images on the page. Can include resized copies of the query image. |
|  [pageTitle](./vision.vision_v1p2beta1.schema_webpage.pagetitle.md) | string \| null | Title for the web page, may contain HTML markups. |
|  [partialMatchingImages](./vision.vision_v1p2beta1.schema_webpage.partialmatchingimages.md) | [Schema$WebImage](./vision.vision_v1p2beta1.schema_webimage.md)<!-- -->\[\] | Partial matching images on the page. Those images are similar enough to share some key-point features. For example an original image will likely have partial matching for its crops. |
|  [score](./vision.vision_v1p2beta1.schema_webpage.score.md) | number \| null | (Deprecated) Overall relevancy score for the web page. |
|  [url](./vision.vision_v1p2beta1.schema_webpage.url.md) | string \| null | The result web page URL. |
