# Sample fluentd configuration for ready cloudwatch logs and exporting to papertrail

This is using the following plugins

* https://github.com/fluent-plugins-nursery/fluent-plugin-cloudwatch-logs
* https://github.com/solarwinds/fluent-plugin-papertrail

# How to use

1. update the fluent.conf to the appropriate settings for your environment
1. build the docker image
1. publish the image
1. deploy image with the environment variables set (make sure the iam roles for cloudwatch are set correctly)
