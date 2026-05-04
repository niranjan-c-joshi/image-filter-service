# Image Filter Service

Simple Express application that downloads a public image, applies a greyscale filter, and returns the processed image.

## Endpoint

GET /filteredimage?image_url={{IMAGE_URL}}

## Example

http://image-filter-env.eba-metrshk8.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/9/9a/Gull_portrait_ca_usa.jpg

## Deployment

Deployed on AWS Elastic Beanstalk using Node.js.

## Tech Stack

- Node.js
- Express
- Jimp
- AWS Elastic Beanstalk