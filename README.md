# Project Bletilla: Generating the thumbnail of an image using Lambda and Node.js and storing the same in a target S3 Bucket.


Generating a thumbnail of an image using AWS Lambda.

## Description

This sample project demonstrate the capability of generating a thumbnail of an uploaded image uploaded to a S3 Bucket. A Lambda is triggered using S3 event notification which uses Node.js runtime and Jimp module to generate the thumbnail and uploads the same to the target S3 bucket.

![Project Bletilla - Design Diagram](https://blog.subhamay.com/wp-content/uploads/2023/01/42_Bletilla_1_1_Architecture_Diagram.png)

## Getting Started

### Dependencies

* Need to have Node.js installed.
* Install Serverless (https://www.serverless.com) Framework and configure the eame.

### Installing

* Clone the repository.
* Follow the blog post to create and stack and then delete the same once done experimenting.

### Executing program

* Upload a sample PNG image into the source S3 Bucket using AWS Console or CLI
* CLI Command to upload an image
```
aws s3 cp sample.png <s3 bucket uri>
```

## Help

Post message in my blog (https://blog.subhamay.com)


## Authors

Contributors names and contact info

Subhamay Bhattacharyya  - [subhamay.aws@gmail.com](https://blog.subhamay.com)

## Version History

* 0.2
    * Various bug fixes and optimizations
    * See [commit change]() or See [release history]()
* 0.1
    * Initial Release

## License

This project is licensed under Subhamay Bhattacharyya. All Rights Reserved.

## Acknowledgments

Inspiration, code snippets, etc.
* [Paulo Dichone ](https://www.linkedin.com/in/paulo-dichone/)
* [Riyaz Sayad](https://www.linkedin.com/in/riyazsayyad/)
* [Rajdeep Saha](https://www.linkedin.com/in/rajdeep-sa-at-aws/)
