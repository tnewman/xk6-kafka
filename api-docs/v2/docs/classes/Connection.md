[**xk6-kafka**](../README.md)

---

# ~~Class: Connection~~

Defined in: [index.d.ts:533](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L533)

## Deprecated

Use `AdminClient` instead. `Connection` remains as a compatibility alias in v2.x.

## Constructors

### Constructor

> **new Connection**(`connectionConfig`): `Connection`

Defined in: [index.d.ts:540](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L540)

#### Parameters

##### connectionConfig

[`ConnectionConfig`](../interfaces/ConnectionConfig.md)

Connection configuration.

#### Returns

`Connection`

- Connection instance.

## Methods

### ~~close()~~

> **close**(): `void`

Defined in: [index.d.ts:566](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L566)

#### Returns

`void`

- Nothing.

#### Destructor

#### Description

Close the connection.

---

### ~~createTopic()~~

> **createTopic**(`topicConfig`): `void`

Defined in: [index.d.ts:547](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L547)

#### Parameters

##### topicConfig

[`TopicConfig`](../interfaces/TopicConfig.md)

Topic configuration.

#### Returns

`void`

- Nothing.

#### Method

Create a new topic.

---

### ~~deleteTopic()~~

> **deleteTopic**(`topic`): `void`

Defined in: [index.d.ts:554](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L554)

#### Parameters

##### topic

`string`

Topic name.

#### Returns

`void`

- Nothing.

#### Method

Delete a topic.

---

### ~~listTopics()~~

> **listTopics**(): `string`[]

Defined in: [index.d.ts:560](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L560)

#### Returns

`string`[]

- Topics.

#### Method

List topics.
