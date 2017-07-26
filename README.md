## Experimenting with OCR

#### Followed along with tutorial:
https://cloud.google.com/functions/docs/tutorials/ocr

The image being analyzed is hardcorded in request.json.
Just change the imageUri to desired image and run the following command in cURL:

```
$ curl -v -s -H "Content-Type: application/json"     https://vision.googleapis.com/v1/images:annotate?key=[API KEY GOES HERE]     --data-binary @request.json
```
