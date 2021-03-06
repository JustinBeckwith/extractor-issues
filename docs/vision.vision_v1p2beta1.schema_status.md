<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p2beta1](./vision.vision_v1p2beta1.md) &gt; [Schema$Status](./vision.vision_v1p2beta1.schema_status.md)

## vision\_v1p2beta1.Schema$Status interface

The `Status` type defines a logical error model that is suitable for different programming environments, including REST APIs and RPC APIs. It is used by \[gRPC\](https://github.com/grpc). Each `Status` message contains three pieces of data: error code, error message, and error details.

You can find out more about this error model and how to work with it in the \[API Design Guide\](https://cloud.google.com/apis/design/errors).

<b>Signature:</b>

```typescript
export interface Schema$Status 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [code](./vision.vision_v1p2beta1.schema_status.code.md) | number \| null | The status code, which should be an enum value of google.rpc.Code. |
|  [details](./vision.vision_v1p2beta1.schema_status.details.md) | Array&lt;{ \[key: string\]: any; }&gt; \| null | A list of messages that carry the error details. There is a common set of message types for APIs to use. |
|  [message](./vision.vision_v1p2beta1.schema_status.message.md) | string \| null | A developer-facing error message, which should be in English. Any user-facing error message should be localized and sent in the google.rpc.Status.details field, or localized by the client. |

