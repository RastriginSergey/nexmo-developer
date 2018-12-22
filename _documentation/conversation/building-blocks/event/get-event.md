---
title: Get an Event
---

# Get an Event

In this building block you will see how to get an Event.

## Example

Ensure the following variables are set to your required values using any convenient method:

Key | Description
-- | --
`CONVERSATION_ID` | The unique ID of the Conversation.
`EVENT_ID` | The unique ID of the Event.

```building_blocks
source: '_examples/conversation/event/get-event'
application:
  use_existing: |
    You will need to use an existing Application that contains a Conversation in order to be able to create an Event and then retrieve details for one. See the Create Conversation building block for information on how to create an Application and some sample Conversations.
```

## Try it out

When you run the code you will get the specified Event.