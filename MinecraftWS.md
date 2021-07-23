# Websocket Documentation
## Subscribe
```json
{
  "header": {
    "version": 1,
    "requestId": "12345",
    "messageType": "commandRequest",
    "messagePurpose": "subscribe"
  },
  "body": {
    "eventName": "PlayerMessage"  // Event Name
  },
}
  ```
`requestId` - Can be any string, Highly recommended to use UUIDv4.

`eventName` - String, event name. See [Events](#events)
## Events
...
