# Websocket Documentation
## Subscribe
```json
{
  "header": {
    "version": 1,
    "requestId": "12345", // Can be anything, highly recommended to use a UUIDv4
    "messageType": "commandRequest",
    "messagePurpose": "subscribe"
  },
  "body": {
    "eventName": "PlayerMessage"  // Event Name
  },
}
  ```
