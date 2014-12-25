Provides basic stats about S3 buckets as a New Relic plugin:
- number of objects
- bucket size
- time since last object modification

Fork and customize if you need additional statistics.

## Install

1. Download the latest version from `https://github.com/adstage/newrelic_s3_plugin/`
1. Extract to the location you want to run the agent from
1. Edit `config/newrelic_plugin.yml`
  1. replace "YOUR_LICENSE_KEY_HERE" with your New Relic license key
  1. replace AWS credentials with your credentials
  1. Copy bucket config and put in bucket region and name for each bucket you want to monitor
1. run `./newrelic_s3_agent`

For bonus points run under supervision. We recommend runit.
