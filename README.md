# CAUTION: THIS MIGHT BE AGAINST YOUTUBE'S T&C
AI:
>Under YouTube Terms of Service and the YouTube Studio / API policies, there’s a consistent rule:
>You may not access, modify, or control YouTube services through automated means except via officially supported APIs or features.
>
>This includes: Scripts that simulate clicks, DOM automation, Headless or injected behavior, Anything that bypasses intended UI flows, Your script does exactly that (even though it’s harmless and local).
>So strictly, on paper: **Yes — UI automation is not permitted**.

However, I only found about abuot it after I have wrote the code and tested it.  
But, just to be safe, I **_did add simulated human random delays in the code_** so it will be slightly slower than the original code.


# Steps:
1. Open your YouTube Studio Videos/Shorts/Livestreams page.
2. Filter the videos to only show Drafts.
3. Scroll to the bottom and change the number of videos per page if required.
4. Open Developer Mode(F12) on your browser and find where the console window is. This will come handy later.
5. Open a notepad window and copy the entire contents of youtube-publish-drafts.js and paste it into the Console.
6. In this notepad find this line and change it whatever you prefer:
   const VISIBILITY = 'Unlisted'; // 'Public' / 'Private' / 'Unlisted'
7. Copy the entire code and paste it into the console from step 5 and press Enter Key.
8. Don't interrupt the process.


