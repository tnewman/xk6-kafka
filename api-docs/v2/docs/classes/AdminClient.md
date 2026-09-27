[**xk6-kafka**](../README.md)

---

# Class: AdminClient

Defined in: [index.d.ts:512](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L512)

## Classdesc

AdminClient connects to Kafka for topic administration.

## Example

```javascript
// In init context
const adminClient = new AdminClient({
  brokers: ["localhost:9092"],
});

// In VU code (default function)
const topics = adminClient.listTopics();

// In teardown function
adminClient.close();
```

## Constructors

### Constructor

> **new AdminClient**(`connectionConfig`): `AdminClient`

Defined in: [index.d.ts:513](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L513)

#### Parameters

##### connectionConfig

[`ConnectionConfig`](../interfaces/ConnectionConfig.md)

#### Returns

`AdminClient`

## Methods

### close()

> **close**(): `void`

Defined in: [index.d.ts:525](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L525)

#### Returns

`void`

---

### createTopic()

> **createTopic**(`topicConfig`): `void`

Defined in: [index.d.ts:514](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L514)

#### Parameters

##### topicConfig

[`TopicConfig`](../interfaces/TopicConfig.md)

#### Returns

`void`

---

### deleteTopic()

> **deleteTopic**(`topic`): `void`

Defined in: [index.d.ts:515](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L515)

#### Parameters

##### topic

`string`

#### Returns

`void`

---

### getMetadata()

> **getMetadata**(`topic`): [`TopicMetadata`](../interfaces/TopicMetadata.md)

Defined in: [index.d.ts:517](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L517)

#### Parameters

##### topic

`string`

#### Returns

[`TopicMetadata`](../interfaces/TopicMetadata.md)

---

### initializeConsumerGroupOffsets()

> **initializeConsumerGroupOffsets**(`config`): [`ConsumerGroupOffset`](../interfaces/ConsumerGroupOffset.md)[]

Defined in: [index.d.ts:522](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L522)

Reset an inactive consumer group to a snapshot of the current end offset
of every partition in the supplied topics.

#### Parameters

##### config

[`ConsumerGroupOffsetsConfig`](../interfaces/ConsumerGroupOffsetsConfig.md)

#### Returns

[`ConsumerGroupOffset`](../interfaces/ConsumerGroupOffset.md)[]

---

### listTopics()

> **listTopics**(): [`TopicInfo`](../interfaces/TopicInfo.md)[]

Defined in: [index.d.ts:516](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L516)

#### Returns

[`TopicInfo`](../interfaces/TopicInfo.md)[]
