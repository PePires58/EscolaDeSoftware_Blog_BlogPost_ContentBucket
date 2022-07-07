## Escola de Software - Blog - BlogPost Content Bucket

In this repository, we're creating the bucket to store the Blog Post content. We are doing this because is the best practice to upload big files into S3 and reference it on DynamoDb instead of recording the content into DynamoDb table.

Each BlogPost has it own BlogContent file into this S3 bucket.
