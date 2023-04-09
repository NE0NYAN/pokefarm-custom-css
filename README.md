# pokefarm-custom-css
A collection of custom CSS rulesheets for PokéFarm Q

## aboutme-pokepanel-template.css
CSS I use for my About section. Turns default interactive pokepanels into compact buttons (fits 3 per line). Wrap everything in [center] tags for proper spacing, use unordered lists for text.

## egg-labels.css
Reveals the names of eggs (even unhatched ones) in Lab, Party, Shelter and Daycare (requires SpyGlass). ***Only fully tested and supported in Chrome!*** Notably, this is an experimental feature in Firefox and requires [enabling the `:has` selector flag](https://stackoverflow.com/questions/73936048/how-do-you-enable-has-selector-on-firefox). Even then, in Firefox the Lab labels don't seem to work properly, but the other labels should.

## field-tweaks.css
A collection of Field tweaks designed to work alongside the QoL "Sort by berries" setting. Repositions and enlarges the correct berry recipients and truncates long field names to enable mass clicking without ever moving the mouse (can still view full field name by hovering the mouse cursor over it). Also makes the fed/unfed counter more visible.

## lab-daycare-tweaks.css
Assorted minor tweaks such as: hide the option to use Lab Reloaders, highlight Lab Reload button when ready, highlight shelter area when QoL has found eggs, hide own profile notification from multi-profile view.

## party-big-buttons.css
Places a ***massive*** button on the bottom of the screen to easily click through whole parties in single and multi view. Works with or without QoL.
