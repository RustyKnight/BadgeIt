#  BadgeIt

`BadgeIt` is a simple mac command line utility that adds a text "banner" and "alpha" or "beta" badge to the App icon

"But wait, there's already a tool that does this [HazAT/badge](https://github.com/HazAT/badge), why shouldn't I just it?", you say.

The answer is simple.  You should.  If it works for you and does the job you need it to, then you should use it, it's really great.

"But if it's so great, why did you create BadgeIt?", you ask.

Well, simply, it wasn't working for me, not enitrly.

* I didn't like the fact that the banner did occupy more vertical space, taking into consideration the bezel applied by Apple, which often cropped the text or forced me to offset the banner in away that didn't really look nice (okay, this is a highlight to the user that this is not a app store version of the app, but why can't I have it look nice?)
* The text can "collapse" in on itself if it's long.  I was simply putting the version and build number across the top of the banner and found that some version values would "collapse" if the text was to long.  This is probably a mixture of issues with SVG and image majic
* I don't like that it didn't, some how, make backups of the original icons and continue to use those when creating new badges - it's a nick pick, but it makes the build process a little more complicated - espeically when you're releasing to multiple destinations and they have different business rules

![Assets/BadgedIcon.png](Assets/BadgedIcon.png?raw=1)

