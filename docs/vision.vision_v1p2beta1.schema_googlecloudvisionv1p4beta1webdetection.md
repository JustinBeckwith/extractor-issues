<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p2beta1](./vision.vision_v1p2beta1.md) &gt; [Schema$GoogleCloudVisionV1p4beta1WebDetection](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetection.md)

## vision\_v1p2beta1.Schema$GoogleCloudVisionV1p4beta1WebDetection interface

Relevant information for the image from the Internet.

<b>Signature:</b>

```typescript
export interface Schema$GoogleCloudVisionV1p4beta1WebDetection 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [bestGuessLabels](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetection.bestguesslabels.md) | [Schema$GoogleCloudVisionV1p4beta1WebDetectionWebLabel](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetectionweblabel.md)<!-- -->\[\] | The service's best guess as to the topic of the request image. Inferred from similar images on the open web. |
|  [fullMatchingImages](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetection.fullmatchingimages.md) | [Schema$GoogleCloudVisionV1p4beta1WebDetectionWebImage](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetectionwebimage.md)<!-- -->\[\] | Fully matching images from the Internet. Can include resized copies of the query image. |
|  [pagesWithMatchingImages](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetection.pageswithmatchingimages.md) | [Schema$GoogleCloudVisionV1p4beta1WebDetectionWebPage](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetectionwebpage.md)<!-- -->\[\] | Web pages containing the matching images from the Internet. |
|  [partialMatchingImages](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetection.partialmatchingimages.md) | [Schema$GoogleCloudVisionV1p4beta1WebDetectionWebImage](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetectionwebimage.md)<!-- -->\[\] | Partial matching images from the Internet. Those images are similar enough to share some key-point features. For example an original image will likely have partial matching for its crops. |
|  [visuallySimilarImages](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetection.visuallysimilarimages.md) | [Schema$GoogleCloudVisionV1p4beta1WebDetectionWebImage](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetectionwebimage.md)<!-- -->\[\] | The visually similar image results. |
|  [webEntities](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetection.webentities.md) | [Schema$GoogleCloudVisionV1p4beta1WebDetectionWebEntity](./vision.vision_v1p2beta1.schema_googlecloudvisionv1p4beta1webdetectionwebentity.md)<!-- -->\[\] | Deduced entities from similar images on the Internet. |

