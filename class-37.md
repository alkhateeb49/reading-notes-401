# Read 37

## Introduction to Amazon S3

Amazon S3 has a simple web services interface that you can use to store and retrieve any amount of data, at any time, from anywhere on the web. It gives any developer access to the same highly scalable, reliable, fast, inexpensive data storage infrastructure that Amazon uses to run its own global network of web sites. The service aims to maximize benefits of scale and to pass those benefits on to developers.

### Advantages of using Amazon S3

Amazon S3 is intentionally built with a minimal feature set that focuses on simplicity and robustness. Following are some of the advantages of using Amazon S3:

- Creating buckets
- Storing data
- Downloading data
- Permissions 
- Standard interfaces 

## S3 with Amplify

The Amplify Storage category provides an interface for managing user content for your app in public, protected, or private storage buckets. The Storage category comes with default built-in support for Amazon Simple Storage Service (S3). The Amplify CLI helps you to create and configure the storage buckets for your app. The Amplify AWS S3 Storage plugin leverages Amazon S3.

To initialize the Amplify Auth and Storage categories you call Amplify.`addPlugin()` method for each category. To complete initialization call `Amplify.configure()`.
