# get-azendoo-data-back

The notebook uses selenium to scrap azendoo data (the login step has to be done manually).

All the posts are in the home page, but the bot has to scroll down (can be very long).
Then, once the full page is loaded, posts are unrolled, and parsed into an array of python dict.
