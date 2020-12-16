# google-dai-live-channels
Demo page for mixing Google DAI stream and other live stream

### To show

`id3-events.json` keeps sending even Google DAI stream is not used. We need to have a stop function to avoid DAI SDK stops sending info when we are playing other stream.

This is a common use case for us when user switches to live TV channels that is not with DAI.
