<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@google/vision](./vision.md) &gt; [vision\_v1p1beta1](./vision.vision_v1p1beta1.md) &gt; [Resource$Projects$Locations$Images](./vision.vision_v1p1beta1.resource_projects_locations_images.md) &gt; [annotate](./vision.vision_v1p1beta1.resource_projects_locations_images.annotate.md)

## vision\_v1p1beta1.Resource$Projects$Locations$Images.annotate() method

Run image detection and annotation for a batch of images.

<b>Signature:</b>

```typescript
annotate(params: Params$Resource$Projects$Locations$Images$Annotate, options: StreamMethodOptions): GaxiosPromise<Readable>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  params | [Params$Resource$Projects$Locations$Images$Annotate](./vision.vision_v1p1beta1.params_resource_projects_locations_images_annotate.md) | Parameters for request |
|  options | StreamMethodOptions | Optionally override request options, such as <code>url</code>, <code>method</code>, and <code>encoding</code>. |

<b>Returns:</b>

GaxiosPromise&lt;Readable&gt;

A promise if used with async/await, or void if used with a callback.

## Example


```js
// Before running the sample:
// - Enable the API at:
//   https://console.developers.google.com/apis/api/vision.googleapis.com
// - Login into gcloud by running:
//   `$ gcloud auth application-default login`
// - Install the npm module by running:
//   `$ npm install googleapis`

const {google} = require('googleapis');
const vision = google.vision('v1p1beta1');

async function main() {
  const auth = new google.auth.GoogleAuth({
    // Scopes can be specified either as an array or as a single, space-delimited string.
    scopes: [
      'https://www.googleapis.com/auth/cloud-platform',
      'https://www.googleapis.com/auth/cloud-vision',
    ],
  });

  // Acquire an auth client, and bind it to all future calls
  const authClient = await auth.getClient();
  google.options('auth', authClient);

  // Do the magic
  const res = await vision.projects.locations.images.annotate({
    // Optional. Target project and location to make a call.
    //
    // Format: `projects/{project-id\}/locations/{location-id\}`.
    //
    // If no parent is specified, a region will be chosen automatically.
    //
    // Supported location-ids:
    //     `us`: USA country only,
    //     `asia`: East asia areas, like Japan, Taiwan,
    //     `eu`: The European Union.
    //
    // Example: `projects/project-A/locations/eu`.
    parent: 'projects/my-project/locations/my-location',

    // Request body metadata
    requestBody: {
      // request body parameters
      // {
      //   "parent": "my_parent",
      //   "requests": []
      // }
    },
  });
  console.log(res.data);

  // Example response
  // {
  //   "responses": []
  // }
}

main().catch(e => {
  console.error(e);
  throw e;
});


```
