# get S3url
If you want to get url to had limitd time, you can use it.

You have to fill your infomation.
> 'aws_access_key_id', 'aws_secret_access_key', 'bucket_name'
```python
conn = S3Connection('aws_access_key_id', 'aws_secret_access_key', host='s3.amazonaws.com')
bucket = conn.get_bucket('bucket_name')
```

### Reference
> http://boto.cloudhackers.com/en/latest/index.html