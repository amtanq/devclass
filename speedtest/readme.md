## SpeedTest Summary
- Working of speed test websites
- Different payload generation techniques
- How to listen to upload / download events
- How to signal an ongoing http request
- Elegant storage / bandwidth conversion
- Deploying static application via S3

### Commands
```bash
$ dd if=/dev/urandom of=random bs=1G count=1
$ du -h random
$ aws s3 mb s3://bucket
$ aws s3 cp . s3://bucket --acl public-read --recursive
```