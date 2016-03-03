# AWS SNS to HipChat gateway

Simple SNS endpoint to forward notifications received from SNS to HipChat.

Just needs the following environment variables set:

* HIPCHAT_V2_TOKEN
* HIPCHAT_ROOM_ID

To run:

    export HIPCHAT_V2_TOKEN=yourapitokenhere
    export HIPCHAT_ROOM_ID=12345
    ./sns-to-hipchat localhost 1999

Where 'localhost' is the hostname and 1999 is the port number.

