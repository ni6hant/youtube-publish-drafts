# THIS MIGHT BE AGAINST YOUTUBE'S T&C
AI:"
Under YouTube Terms of Service and the YouTube Studio / API policies, there’s a consistent rule:
*You may not access, modify, or control YouTube services through automated means except via officially supported APIs or features.*

This includes:
Scripts that simulate clicks, DOM automation, Headless or injected behavior, Anything that bypasses intended UI flows, Your script does exactly that (even though it’s harmless and local). So strictly, on paper: Yes — UI automation is not permitted.
"

The problem is I only found this out after I fixed the code and used it so I thought might as well upload it somewhere.

# Steps
1. Open your Youtube Studio Page.
2. Scroll to bottom and increase the number of videos avaialable on this page to as much as you want. Also, filter them. As the script only works on the first page.
3. Change the Visibility you want on your videos in the code itself in line 15 where it says:  
   `const VISIBILITY = 'Unlisted'; // 'Public' / 'Private' / 'Unlisted'.`
   By default it's set to Unlisted. Change it to whatever you want but changing status after it's out of draft is pretty easy in youtube studio.
5. Press F12/Open Developer Mode on your browser and find the console window.
6. Copy the entire content of youtube-publish-drafts.js and paste it into the Console.

   
