# Munin plugin for Beanstalkd

This plugin lets you get munin graphs with all Beanstalkd jobs counts.

## Contents

- [Usage](#usage)

## Usage

Go to the [latest release page](https://github.com/alexsoft/munin-beanstalk/releases/latest), download phar-archive of into munin plugins directory.

For example (phar file URL might be different):

```sh
    wget https://github.com/alexsoft/munin-beanstalk/releases/download/v1.0.0/munin-beanstalk.phar
    chmod a+x munin-beanstalk.phar
    sudo mv munin-beanstalk.phar /etc/munin/plugins/beanstalk
```

Then restart `munin-node` service and in 5 minutes you will get first counts.
