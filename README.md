# Procedural-Sky-with-Time-of-Day
This is a simple tech demo for creating a day and night cycle with adjusting sky, light, atmosphere and fog.

How it works:
I am starting with determing the length of the day in seconds and counting the time. The current time acts then as my evaluation point for all the settings for Sun, Light, Atmosphere, Exposure and Fog. I added the option of using the different ambient modes Unity offers.

Explaining this is rather hard as it really just is a bunch of gradients and curves which we then evaluate depending on the current time. I highly suggest taking a look at the source code, you’ll see it is a rather simple approach but it gives you a lot more freedom in creating the sky instead of just setting three set skybox settings.
