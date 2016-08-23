# S3 Blueprint Example

1. Make sure you have Node/NPM installed on your computer.
1. Go to S3 in the services menu on AWS and create two new buckets - one for image uploads and one for resized images. *Note bucket names must be unique so you may have to add random numbers to the bucket name.*
1. In IAM, create a new user and add administrative privilages.
1. Create a new folder on your local machine to store this lambda function with third party modules.
1. `cd` into the folder you just created.
1. `npm install async gm`
1. Copy the code for lambda.
1. Run this command from the terminal to create a zip file: `zip -r CreateThumbnail.zip *`