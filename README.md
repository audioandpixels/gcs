## Configuration files for Google Cloud Storage buckets

Set bucket CORS policy:
gsutil cors set cors_config.json gs://am-tmp

Set bucket life cycle:
gsutil lifecycle set lifecycle_config.json gs://am-tmp