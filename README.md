brave-youtube-filter

A custom filter list for the Brave browser that removes most of YouTube’s algorithmic and slop features.

Hides - recommendations, Shorts, autoplay panels, and playables.
Keeps - Subscriptions, manual search, and direct links.

An attempt to replicate what Youtube decluttering browser extensions do without it doing ??? with your data.

What it does
Removes homepage recommendations
Hides sidebar suggestions while watching
Disables end screen video suggestions
Removes autoplay / “Up next”
Hides Shorts (shelves + sidebar entry)
Removes gaming/playables sections

Customising
The list is meant to be edited.
If there’s something you want to keep, just comment it out by adding ! at the start of the line:

! www.youtube.com##ytd-watch-next-secondary-results-renderer

YouTube changes often, I'll update it when it breaks for me.

Install (Brave browser, might work on certain add blockers but not tested)
Open:

brave://settings/shields/filters
Scroll to Custom filters
Paste the contents of filters.txt into the box
Save
Refresh YouTube tabs

Limitations
YouTube regularly changes its layout, so some filters may break over time
Doesn’t block ads 
Some recommendation elements may still appear in edge cases (e.g. channel pages, embeds)
Logged-out experience may behave differently from logged-in
