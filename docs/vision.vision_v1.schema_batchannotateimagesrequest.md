<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1](./vision.vision_v1.md) &gt; [Schema$BatchAnnotateImagesRequest](./vision.vision_v1.schema_batchannotateimagesrequest.md)

## vision\_v1.Schema$BatchAnnotateImagesRequest interface

Multiple image annotation requests are batched into a single service call.

<b>Signature:</b>

```typescript
export interface Schema$BatchAnnotateImagesRequest 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [parent](./vision.vision_v1.schema_batchannotateimagesrequest.parent.md) | string \| null | Optional. Target project and location to make a call.<!-- -->Format: <code>projects/{project-id\}/locations/{location-id\}</code>.<!-- -->If no parent is specified, a region will be chosen automatically.<!-- -->Supported location-ids: <code>us</code>: USA country only, <code>asia</code>: East asia areas, like Japan, Taiwan, <code>eu</code>: The European Union.<!-- -->Example: <code>projects/project-A/locations/eu</code>. |
|  [requests](./vision.vision_v1.schema_batchannotateimagesrequest.requests.md) | [Schema$AnnotateImageRequest](./vision.vision_v1.schema_annotateimagerequest.md)<!-- -->\[\] | Required. Individual image annotation requests for this batch. |
