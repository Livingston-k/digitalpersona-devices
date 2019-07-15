<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@digitalpersona/devices](./devices.md) &gt; [CardsReader](./devices.cardsreader.md) &gt; [subscribe](./devices.cardsreader.subscribe.md)

## CardsReader.subscribe() method

Starts listening for card reader events.

<b>Signature:</b>

```typescript
subscribe(reader?: string): Promise<void>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  reader | <code>string</code> | an optional name of a card reader to listen. If no name is provided, the API will start listening all card readers. |

<b>Returns:</b>

`Promise<void>`
