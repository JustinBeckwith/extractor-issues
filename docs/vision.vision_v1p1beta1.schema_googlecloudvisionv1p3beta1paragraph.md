<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p1beta1](./vision.vision_v1p1beta1.md) &gt; [Schema$GoogleCloudVisionV1p3beta1Paragraph](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p3beta1paragraph.md)

## vision\_v1p1beta1.Schema$GoogleCloudVisionV1p3beta1Paragraph interface

Structural unit of text representing a number of words in certain order.

<b>Signature:</b>

```typescript
export interface Schema$GoogleCloudVisionV1p3beta1Paragraph 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [boundingBox](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p3beta1paragraph.boundingbox.md) | [Schema$GoogleCloudVisionV1p3beta1BoundingPoly](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p3beta1boundingpoly.md) | The bounding box for the paragraph. The vertices are in the order of top-left, top-right, bottom-right, bottom-left. When a rotation of the bounding box is detected the rotation is represented as around the top-left corner as defined when the text is read in the 'natural' orientation. For example: \* when the text is horizontal it might look like: 0\-\-\--1 \| \| 3\-\-\--2 \* when it's rotated 180 degrees around the top-left corner it becomes: 2\-\-\--3 \| \| 1\-\-\--0 and the vertex order will still be (0, 1, 2, 3). |
|  [confidence](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p3beta1paragraph.confidence.md) | number \| null | Confidence of the OCR results for the paragraph. Range \[0, 1\]. |
|  [property](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p3beta1paragraph.property.md) | [Schema$GoogleCloudVisionV1p3beta1TextAnnotationTextProperty](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p3beta1textannotationtextproperty.md) | Additional information detected for the paragraph. |
|  [words](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p3beta1paragraph.words.md) | [Schema$GoogleCloudVisionV1p3beta1Word](./vision.vision_v1p1beta1.schema_googlecloudvisionv1p3beta1word.md)<!-- -->\[\] | List of all words in this paragraph. |

