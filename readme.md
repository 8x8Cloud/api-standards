# 8x8 API Standards

This contains a spectral file that can be extended to set in place 8x8 API Standards.

## How to use this:

In your root directory of your project, create a `.spectral.json` (you can also use yaml if you prefer) file that contains the following:

```json
{
  "extends": [
    "https://raw.githubusercontent.com/8x8Cloud/api-standards/master/spectral.json"
  ]
}
```

With the spectral cli tool, you can lint a OAS or Swagger file like so:

`spectral lint swagger.yaml` (or if you're using json you can pass that in, too).
