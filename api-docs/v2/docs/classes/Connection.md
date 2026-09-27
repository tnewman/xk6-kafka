[**xk6-kafka**](../README.md)

---

# ~~Class: Connection~~

Defined in: [index.d.ts:531](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L531)

## Deprecated

Use `AdminClient` instead. `Connection` remains as a compatibility alias in v2.x.

## Constructors

### Constructor

> **new Connection**(`connectionConfig`): `Connection`

Defined in: [index.d.ts:538](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L538)

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

Defined in: [index.d.ts:564](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L564)

#### Returns

`void`

- Nothing.

#### Destructor

#### Description

Close the connection.

---

### ~~createTopic()~~

> **createTopic**(`topicConfig`): `void`

Defined in: [index.d.ts:545](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L545)

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

Defined in: [index.d.ts:552](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L552)

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

Defined in: [index.d.ts:558](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L558)

#### Returns

`string`[]

- Topics.

#### Method

List topics.
