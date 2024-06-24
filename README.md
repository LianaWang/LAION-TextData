# LAION-TextData
Scene text image data with `text words` and their `coordinates` annotations collected from [LAION-400M dataset](https://laion.ai/blog/laion-400-open-dataset/).

We provide the links of images from LAION-400M dataset, and our mannually annotated `text` and `coordinates` information. Currently, we release `5000` samples with `49866` text annotations with center coordinates.

The following is one sample of the annotation:

```
{
  "index": "part1_000228186", # only a random name
  "url": "https://thesiliconreview.net/administrator/article_image/siliconreview-Googles-face-recognition-technology-to-be-added-into-home-security-camera.jpg", # url of the image, we do not provide downloading following the license of LAION-400M
  "width": 840, # image width
  "height": 449, # image height
  "caption": "Google's face recognition technology to be added into home-security camera", # caption copied from LAION-400M
  "annotations": [ # the annotation of text instances within this image
    {
      "text": "captured",
      "center": [
        183.0,
        57.7
      ]
    },
    {
      "text": "Face",
      "center": [
        124.4,
        53.0
      ]
    },
    {
      "text": "###", # means annotators could not read the text content from the image
      "center": [
        117.0,
        2.0
      ]
    },
    {
      "text": "###", # means annotators could not read the text content from the image
      "center": [
        166.0,
        2.0
      ]
    }
  ]
},
```

## Dataset download

Click to download LAION-TextData dataset from [Baidu Pan](https://pan.baidu.com/s/1bP6_yawegbAAfTOfIURO7A?pwd=q6mb).

## License
Following the LAION-400M, `LAION-TextData` dataset was built for research purposes, and is not meant for any real-world production or application, and is under the most open Creative Common CC-BY 4.0 license. The images are under their copyright.
