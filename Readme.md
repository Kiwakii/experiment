# Deploying a Static Website to AWS S3 using Github Actions 
# Distribute contents using CloudFront and Lambda@Edge  

# Setup a github repository with a couple of simple web pages in a /public directory
  # -- Using VS Code created a simple project to contain index.html and index_a.html files among js files used to
  # -- Configure viewrequest, originrequest and originresponse lambda function   

# Setup two s3 buckets created with us-east-1 region to hold index.html and index_a.html urls respectively 

# Created a repository 'Experiment/Public' in my Github account www.github.com/Kiwakii

# Git init and push git skeleton project to Github.

# Setup and perform Github Action to merge changes into master branch to update the following
  # -- Push changes of index.html to S3 bucket named Subject
  # -- Push changes of index_a.html to S3 bucket named Experiment

# Created CloudFront Distribution and wired it up with s3 buckets already created 

# Create and configure Lambda function to wire up CloudFront Distribution and Lambda@Edge

# Lambda functions create using predefines template available in AWS Developer Guides

# Also leverage is Nodejs scripts available in AWS that randomizes which static files gets invoked when request 
 # gets triggered
