# monitoring-plugin-sophos-license

### Description
Monitor the expiry of services licensed for sophos firewalls.


### Usage

    Usage: check_sophos_license [options]

    Options:
      -h,               --help                      show this help message and exit
      -w WARNING,       --warning=WARNING           [Default: 30] days for warning
      -c CRITICAL,      --critical=CRITICAL         [Default: 15] days for critical
      -H HOSTNAME,      --hostname=HOSTNAME         [Default: localhost] hostname
      -p PORT,          --port=PORT                 [Default: 4444] port
      -u USERNAME,      --username=USERNAME         [Default: admin] username
      -s SECRET,        --secret=SECRET             [Default: admin] password
      -V,               --verify                    [Default: true] verify
      -t TIMEOUT,       --timeout=TIMEOUT           [Default: 15] timeout in seconds
      -a ACCESSTOKEN,   --accesstoken=ACCESSTOKEN   accesstoken


### Install 

Copy check_sophos_license to your plugin folder and create a service/exec in your monitoring engine. 
