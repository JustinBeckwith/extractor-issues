<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p2beta1](./vision.vision_v1p2beta1.md) &gt; [Schema$TextAnnotation](./vision.vision_v1p2beta1.schema_textannotation.md)

## vision\_v1p2beta1.Schema$TextAnnotation interface

TextAnnotation contains a structured representation of OCR extracted text. The hierarchy of an OCR extracted text structure is like this: TextAnnotation -<!-- -->&gt; Page -<!-- -->&gt; Block -<!-- -->&gt; Paragraph -<!-- -->&gt; Word -<!-- -->&gt; Symbol Each structural component, starting from Page, may further have their own properties. Properties describe detected languages, breaks etc.. Please refer to the TextAnnotation.TextProperty message definition below for more detail.

<b>Signature:</b>

```typescript
export interface Schema$TextAnnotation 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [pages](./vision.vision_v1p2beta1.schema_textannotation.pages.md) | [Schema$Page](./vision.vision_v1p2beta1.schema_page.md)<!-- -->\[\] | List of pages detected by OCR. |
|  [text](./vision.vision_v1p2beta1.schema_textannotation.text.md) | string \| null | UTF-8 text detected on the pages. |
