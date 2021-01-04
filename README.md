# Project: Image Lambda

- [GitHub Repository]()

## How to use

- Upload an image to the bucket and resized image will be in "-resized" bucket

## Lambda Function Source Code

- The lambda function code provided by Amazon [tutorial](https://docs.aws.amazon.com/lambda/latest/dg/with-s3-example.html)

## Lambda Use

- Upload an image to [S3 Bucket](https://s3.console.aws.amazon.com/s3/buckets/thumbnail-maker2-resized?region=us-west-2&tab=objects)
- Access thumbnail image in [S3 Bucket -resized](https://s3.console.aws.amazon.com/s3/buckets/thumbnail-maker2-resized?region=us-west-2&tab=objects)

## Issues During Deployment

Still working on it. While installing EB mongo threw an error that crashed multiple things. I was not able to use npm. Had to fix mongodb before errors would resolve. 

## Test Images

![Upload Image](assets/lab18-src-img.png)
![Thumbnail Image](assets/lab18-thumb-img.png)