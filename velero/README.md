# Velero backup

Please note that this Helm chart is misconfigured on purpose by default when no valid `targetCustomizations` are provided.

Depending on the Cloud Provider, Velero backup destinations will differ:

- *AWS* : stored on S3
- *vSphere* : stored on an S3 endpoint, exposed by NetApp ONTap: [https://orw-ntap5-s3.wv.mentorg.com](https://orw-ntap5-s3.wv.mentorg.com)

