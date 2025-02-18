# Buddyboss Custom Profile Fields

Adds custom profile field (Business Name) into the Members directory feed as the name of the user (member loop and in profiles). Using Buddy Boss plugin

This example adds fields "Business Name" as the user's name

## Case 1: Member Loop

The member's template path is here:

public_html/wp-content/plugins/buddyboss-platform/bp-templates/bp-nouveau/buddypress/members/members-loop.php

Add or Create members-loop.php to your child theme: /buddypress/members/members-loop.php

This code has been changed on line 160, the class is member-name.

## Case 2: Profile

The path is public_html/wp-content/plugins/buddyboss-platform/bp-templates/bp-nouveau/buddypress/members/single/cover-image-header.php

Because the template used in this case is: cover-image-header.php and NOT members-header.php

Add or Create cover-image-header.php to your child theme. The original template can be overridden by copying it to yourtheme/buddypress/members/single/cover-image-header.php

This code has been changed on line 145, the class is user-nicename.


Both fields are wrapped in a h2 class to style it accordingly.
Add custom css styling div class(es). You can add it to the child theme style.css, or the site customizer CSS or other area such as Custom CSS plugin.