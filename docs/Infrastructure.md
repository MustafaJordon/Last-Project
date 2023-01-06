# Udagram infrastructure
Here is the general infrastructure of Udagram-api

## Database
  Postgres database located on AWS RDS which has many advantages like it is easy to be configured, easy to have backups and can be provided through different availabilty zones.

## Frontend
  Udagram-api uses Angular as the frontend framework which is a cross-platform framework, has inituitive UI&UX, Easy for testing and univarsal server supported. Frontend files are hosted on AWS S3 bucket named mustafa-new-bucket.

## Backend
  Udagram-api backend is based on Node.js hosted on AWS elastic beanstalk which is a perfect place to host backend of web applications because of it makes it even easier for developers to quickly deploy and manage applications in the AWS Cloud

## CI/CD Pipeline
  Udagram-api uses continous integration continious delivery technique through CircleCI pipeline to provide an easy way for the development and production processes to have an easy workflow which can help in faster delivery of features and faster error detection.