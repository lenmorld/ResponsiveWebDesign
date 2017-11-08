min-width: allow element to shrink properly like normal
      but have a limit on how small it could get

max-width: allows elements to be set to a  specified limit
            but it could also be constrained to smaller


@media only screen and (max-width: 600px)  {...}
What this query really means, is "If [device width] is less than or equal to 600px, then do {...}"
So if the email is opened on an iPhone 5S, with a screen width of 320px,
the media query will trigger and all of the styles contained in { ... } will take effect.


@media only screen and (min-width: 600px)  {...}
What this query really means, is "If [device width] is greater than or equal to 600px, then do {...}"

So if the email is opened on an iPhone 5S, with a screen width of 320px,
the media query will not trigger and the styles contained in { ... } will not take effect.


@media only screen and (max-width: 600px) and (min-width: 400px)  {...}
The query above will trigger only for screens that are 600-400px wide. This can be used to target specific devices with known widths.


specific ranges, specifying breakpoints for each device type
https://stackoverflow.com/questions/13637106/what-are-the-best-width-ranges-for-media-queries



box-sizing: border-box
The width and height properties (and min/max properties) includes content, padding and border, but not the margin





image
https://static.pexels.com/photos/39811/pexels-photo-39811.jpeg
