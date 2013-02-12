# jpholidayp

Is it holiday today in Japan?

## SYNOPSIS

    jpholidayp

## DESCRIPTION

Check "Is it holiday today?" in Japan.

No arguments, and no output.
Reports as exit status:

* 0 (success): holiday
* 1: not holiday

"Holiday" means:

* Sunday and Saturday
* In Google Calendar's "Japanese Holiday"

It creates cache file at ~/.jpholidayp directory.

## EXAMPLES

usages in crontab.

    jpholidayp && some-command

Run some-command in holiday.

    jpholidayp || some-command

Run some-command in weekday.

## AUTHOR

emasaka