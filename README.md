# JSRadio
A time-based synchronized online radio project that doesn't require external servers or a connection between different devices. JSRadio uses moment.js and howler.js to sync an audio file between different devices down to the second to give the impression that the audio is being brodcasted live.

## How it works
JSRadio works by seperating the times of day into four 6 hour chunks, with one radio file being played during each one of these chunks. It uses moment.js to get the time since midnight in seconds and seeks the audio at the specific spot based on the devices time.

If it doesn't make sense, it will when you look at the code and mess around with it. I think it's pretty cool.

## How can I implement this on my site?
I have a gist avalible for use [here](https://gist.github.com/nathanaccidentally/2fbf759cf3489346f1e0782a0a7bdb28) that you can use on your website! All you need to do is have a 6/12hr file source along with moment.js and howler.js already in your project folder.
