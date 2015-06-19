# gitlog-coffee
Generates a log file from certain prefixes.
---
[![NPM](https://nodei.co/npm/gitlogs-coffee.png?downloads=true&stars=true)](https://nodei.co/npm/gitlogs-coffee/)
---
**Usage**

Used to generate logs for between the current tag and the second most recent tag.
Useful to see what was done between builds.

By default a file called log.txt is created with the messages in the same directory for which the task was called.


___
**Install**

```npm install gitlogs-coffee```
___
**Example**
In cmd or terminal, depending on your Operating System, simply type.
```
coffee createLogs Added done 123 abc
```
This will take all the commits between the current tag and the second most recent tag that contains the any one of the four prefixes specified above,
[Added, done, 123, abc].
Each commit will be added to a file called log.txt
