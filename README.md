Shell script for getting fragments of logfiles from a specific time period.

<p align="center">
    <img src="https://chr15m.github.io/logsnip/screencast.svg"/>
</p>

# Install

```shell
curl https://chr15m.github.io/logsnip/logsnip > ~/bin/logsnip && chmod 755 ~/bin/logsnip
```

# Usage

```
Usage: logsnip HOST LOGTYPE TIMESPEC MINUTES

  LOGTYPE   syslog, auth.log, uwsgi, nginx/error.log, nginx/access.log
  TIMESPEC  anything you can pass to the 'date' command.
            e.g. 'now' or '2012-01-01 13:02' or '2:30pm yesterday' etc.
  MINUTES   how many minutes to include up to the specified time (5 mins default)
```

