# MoceanAPI Client Web Plugin for WebRTC Webphone

This is the web plugin for Mocean's API.Mocean account. Sign up for free at [moceanapi.com](https://dashboard.moceanapi.com/register?medium=github&campaign=webphone-plugin).


Usage
---
~~~html

<div id="mocean-web-phone"></div>
<script src="https://cdn.jsdelivr.net/gh/MoceanAPI/moceanapi-webphone/moceanapi-webphone.min.js"></script>
<script>
    CreateWebPhone({
        apiKey: API_KEY,
        apiSecret: API_SECRET,
        callerId: CALLER_ID,
    });
</script>
~~~

**Custom Div ID**
~~~javascript
<div id="CUSTOM_CONTAINER_ID"></div>
<script src="https://cdn.jsdelivr.net/gh/MoceanAPI/moceanapi-webphone/moceanapi-webphone.min.js"></script>
<script>
    CreateWebPhone({
        apiKey: API_KEY,
        apiSecret: API_SECRET,
        callerId: CALLER_ID,
        containerID: CUSTOM_CONTAINER_ID
    });
</script>
~~~
