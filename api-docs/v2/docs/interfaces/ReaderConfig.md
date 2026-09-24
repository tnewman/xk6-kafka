[**xk6-kafka**](../README.md)

---

# Interface: ReaderConfig

Defined in: [index.d.ts:199](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L199)

## Properties

### brokers

> **brokers**: `string`[]

Defined in: [index.d.ts:200](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L200)

---

### commitInterval

> **commitInterval**: `number`

Defined in: [index.d.ts:221](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L221)

---

### connectLogger

> **connectLogger**: `boolean`

Defined in: [index.d.ts:231](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L231)

---

### fetchMessageMaxBytes?

> `optional` **fetchMessageMaxBytes?**: `number`

Defined in: [index.d.ts:211](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L211)

---

### groupBalancers

> **groupBalancers**: [`GROUP_BALANCERS`](../enumerations/GROUP_BALANCERS.md)[]

Defined in: [index.d.ts:219](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L219)

---

### groupId

> **groupId**: `string`

Defined in: [index.d.ts:201](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L201)

---

### ~~groupID?~~

> `optional` **groupID?**: `string`

Defined in: [index.d.ts:203](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L203)

#### Deprecated

Use `groupId` instead.

---

### groupTopics

> **groupTopics**: `string`[]

Defined in: [index.d.ts:204](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L204)

---

### heartbeatInterval

> **heartbeatInterval**: `number`

Defined in: [index.d.ts:220](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L220)

---

### isolationLevel

> **isolationLevel**: [`ISOLATION_LEVEL`](../enumerations/ISOLATION_LEVEL.md)

Defined in: [index.d.ts:233](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L233)

---

### joinGroupBackoff

> **joinGroupBackoff**: `number`

Defined in: [index.d.ts:226](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L226)

---

### maxAttempts

> **maxAttempts**: `number`

Defined in: [index.d.ts:232](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L232)

---

### maxBytes

> **maxBytes**: `number`

Defined in: [index.d.ts:214](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L214)

---

### maxPartitionFetchBytes?

> `optional` **maxPartitionFetchBytes?**: `number`

Defined in: [index.d.ts:212](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L212)

---

### maxPollInterval?

> `optional` **maxPollInterval?**: `string` \| `number`

Defined in: [index.d.ts:217](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L217)

---

### maxWait

> **maxWait**: `string`

Defined in: [index.d.ts:216](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L216)

---

### metadataMaxAge?

> `optional` **metadataMaxAge?**: `number`

Defined in: [index.d.ts:236](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L236)

---

### minBytes

> **minBytes**: `number`

Defined in: [index.d.ts:213](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L213)

---

### offset

> **offset**: `number`

Defined in: [index.d.ts:234](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L234)

---

### partition

> **partition**: `number`

Defined in: [index.d.ts:206](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L206)

---

### partitionWatchInterval

> **partitionWatchInterval**: `number`

Defined in: [index.d.ts:222](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L222)

---

### ~~queueCapacity?~~

> `optional` **queueCapacity?**: `number`

Defined in: [index.d.ts:208](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L208)

#### Deprecated

Use `queuedMinMessages` or `queuedMaxMessagesKbytes` instead.

---

### queuedMaxMessagesKbytes?

> `optional` **queuedMaxMessagesKbytes?**: `number`

Defined in: [index.d.ts:210](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L210)

---

### queuedMinMessages?

> `optional` **queuedMinMessages?**: `number`

Defined in: [index.d.ts:209](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L209)

---

### readBackoffMax

> **readBackoffMax**: `number`

Defined in: [index.d.ts:230](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L230)

---

### readBackoffMin

> **readBackoffMin**: `number`

Defined in: [index.d.ts:229](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L229)

---

### readBatchTimeout

> **readBatchTimeout**: `number`

Defined in: [index.d.ts:215](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L215)

---

### readLagInterval

> **readLagInterval**: `number`

Defined in: [index.d.ts:218](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L218)

---

### rebalanceTimeout

> **rebalanceTimeout**: `number`

Defined in: [index.d.ts:225](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L225)

---

### retentionTime

> **retentionTime**: `number`

Defined in: [index.d.ts:227](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L227)

---

### sasl

> **sasl**: [`SASLConfig`](SASLConfig.md)

Defined in: [index.d.ts:237](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L237)

---

### sessionTimeout

> **sessionTimeout**: `number`

Defined in: [index.d.ts:224](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L224)

---

### socketKeepAlive?

> `optional` **socketKeepAlive?**: `boolean`

Defined in: [index.d.ts:235](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L235)

---

### startOffset

> **startOffset**: [`START_OFFSETS`](../enumerations/START_OFFSETS.md)

Defined in: [index.d.ts:228](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L228)

---

### tls

> **tls**: [`TLSConfig`](TLSConfig.md)

Defined in: [index.d.ts:238](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L238)

---

### topic

> **topic**: `string`

Defined in: [index.d.ts:205](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L205)

---

### watchPartitionChanges

> **watchPartitionChanges**: `boolean`

Defined in: [index.d.ts:223](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L223)
