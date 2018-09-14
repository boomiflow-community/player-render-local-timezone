# render-local-timezone
Includes a snippet (lines 126-133) to render DateTime values in the users local timezone. 

The underlying platform uses UTC for all DateTimes. This setting will work for something like a table (which recognizes that a column is datetime) but it won't work if you're just referencing a UTC timestamp value in a step or presentation (because the platform considers that text value reference to be a string).

Please be aware: the intent is to deprecate these settings and make this the default behavior of the platform.  
