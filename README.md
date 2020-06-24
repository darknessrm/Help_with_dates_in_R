# Help_with_dates_in_R
I'm new in this environment, and i can´t make this code run well.

This is the code:

datestring <- c("January 10, 2012 10:40", "December 9, 2011 9:10")

x <- strptime(datestring, "%B %d, %Y %H:%M")

x

It´s supposed to show this:

[1] "2012-01-10 10:40:00 EST" "2011-12-09 09:10:00 EST"

but i just got this:

[1] NA NA

If i make a mistake in the code, please let me know, i apologize if this is too easy to run.
