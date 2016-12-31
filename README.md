# Facebook Messenger Bot Sample

This is a sample Facebook Messenger Bot application written in Node.js for understanding the basic concepts. Thanks to x-team.com [1] for providing step by step instructions for writing this from scratch.

# Things To Be Improved

Currently the POST /webhook API method does not handle authentication requests, message delivery confirmations, message read notifications, etc [4]. This needs to be handled to avoid unnecessary error messages on the server side.

# References
- [1] http://x-team.com/2016/04/how-to-get-started-with-facebook-messenger-bots/
- [2] https://developers.facebook.com/docs/messenger-platform
- [3] https://github.com/fbsamples/messenger-platform-samples
- [4] https://github.com/fbsamples/messenger-platform-samples/blob/master/node/app.js#L83
