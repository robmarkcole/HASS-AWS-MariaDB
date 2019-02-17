# HASS-AWS-MariaDB
Guide to using a MariaDB instance on AWS as a [recorder](https://www.home-assistant.io/docs/backend/database/) for Home Assistant. I did similar on [GCP](https://github.com/robmarkcole/HASS-Google-Cloud-SQL) but the costs didn't warrant the effort. Lets see if AWS is better in that regard. Ultimately aiming for an AWS backend for HA with S3 buckets for photos and lambda functions for ML? Note that Hassio has a MariaDB addon so configuring to use AWS via an addon might be very straightforward.

* https://aws.amazon.com/rds/mariadb/
* https://www.home-assistant.io/addons/mariadb/
