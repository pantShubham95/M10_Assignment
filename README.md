# This contains the M10 Assignment 

## File Loaded in S3 Bucket:
### Part 1 
#### With First Row Blank
S3 URL:-
s3://mybucketmodule10/charities_bureau_scrape_with_one_row_blank20240413162806.csv

Amazon Resource Name (ARN): - arn:aws:s3:::mybucketmodule10/charities_bureau_scrape_with_one_row_blank20240413162806.csv

#### In Correct Format:
S3 URL:- 
s3://mybucketmodule10/charities_bureau_scrape_with_one_row_blank20240413162806.csv

Amazon Resource Name (ARN): - 
arn:aws:s3:::mybucketmodule10/charities_bureau_scrape_with_one_row_blank20240413162806.csv


### Part 2
#### Data From all pages
S3 URL:- 
s3://mybucketmodule10/charities_bureau_scrape_allpage_20240414152605.csv
Amazon Resource Name (ARN): - 
arn:aws:s3:::mybucketmodule10/charities_bureau_scrape_allpage_20240414152605.csv

## S3 Bucket Policy

{
    "Version": "2012-10-17",
    "Id": "Policy1713041653868",
    "Statement": [
        {
            "Sid": "Stmt1713041645339",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": [
                "arn:aws:s3:::mybucketmodule10/charities_bureau_scrape_20240413162806.csv",
                "arn:aws:s3:::mybucketmodule10/charities_bureau_scrape_with_one_row_blank20240413162806.csv",
                "arn:aws:s3:::mybucketmodule10/charities_bureau_scrape_allpage_20240414152605.csv"
            ]
        }
    ]
}