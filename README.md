# homebridge-platform-ring-video-doorbell
A (Ring Video Doorbell)[https://ring.com/] platform plugin for [Homebridge](https://github.com/nfarina/homebridge).

# Installation
Run these commands:

    % sudo npm install -g homebridge
    % sudo npm install -g homebridge-platform-ring-video-doorbell


# Configuration
Edit `~/.homebridge/config`, inside `"platform": [ ... ]` add:

    { "accessory" : "ring-video-doorbell"
    , "name"      : "Doorbell"
    , "username"  : "user@example.com"
    , "password"  : ""

    // optional
    , "cache"     : 10
    , "options"   : { "verboseP": false }
    }

# Many Thanks
Many thanks to (jeroenmoors)[https://github.com/jeroenmoors] author of
[php-ring-api](https://github.com/jeroenmoors/php-ring-api).