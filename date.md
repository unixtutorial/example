---
description: This pages shows examples of using the date command.
---

# date command examples

## Basic date usage

Just type **date** in the command line:

```
$ date
Wed 29 Jan 2020 12:15:00 GMT
```

## Using templates for formatting output

There's a whole list of variable names that allow you to format the **date** command output to exactly your liking.

Things you can do with this formatting feature:
* show only part of the date info - today's day of the week or today's month or year
* rearrange the order of date fields reported by the command
* rearrange the format of reporting a particular thing - showing two digits for year number instead of four, etc

Here's an example:

```
$ date "+%B %d, %Y"
January 29, 2020
```

## See Also

* [date command](https://www.unixtutorial.org/commands/date)
