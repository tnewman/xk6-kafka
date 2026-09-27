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

Defined in: [index.d.ts:219](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L219)

---

### connectLogger

> **connectLogger**: `boolean`

Defined in: [index.d.ts:229](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L229)

---

### fetchMessageMaxBytes?

> `optional` **fetchMessageMaxBytes?**: `number`

Defined in: [index.d.ts:209](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L209)

---

### groupBalancers

> **groupBalancers**: [`GROUP_BALANCERS`](../enumerations/GROUP_BALANCERS.md)[]

Defined in: [index.d.ts:217](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L217)

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

Defined in: [index.d.ts:218](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L218)

---

### isolationLevel

> **isolationLevel**: [`ISOLATION_LEVEL`](../enumerations/ISOLATION_LEVEL.md)

Defined in: [index.d.ts:231](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L231)

---

### joinGroupBackoff

> **joinGroupBackoff**: `number`

Defined in: [index.d.ts:224](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L224)

---

### maxAttempts

> **maxAttempts**: `number`

Defined in: [index.d.ts:230](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L230)

---

### maxBytes

> **maxBytes**: `number`

Defined in: [index.d.ts:212](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L212)

---

### maxPartitionFetchBytes?

> `optional` **maxPartitionFetchBytes?**: `number`

Defined in: [index.d.ts:210](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L210)

---

### maxPollInterval?

> `optional` **maxPollInterval?**: `string`

Defined in: [index.d.ts:215](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L215)

---

### maxWait

> **maxWait**: `string`

Defined in: [index.d.ts:214](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L214)

---

### metadataMaxAge?

> `optional` **metadataMaxAge?**: `string`

Defined in: [index.d.ts:234](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L234)

---

### minBytes

> **minBytes**: `number`

Defined in: [index.d.ts:211](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L211)

---

### offset

> **offset**: `number`

Defined in: [index.d.ts:232](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L232)

---

### partition

> **partition**: `number`

Defined in: [index.d.ts:206](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L206)

---

### partitionWatchInterval

> **partitionWatchInterval**: `number`

Defined in: [index.d.ts:220](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L220)

---

### queuedMaxMessagesKbytes?

> `optional` **queuedMaxMessagesKbytes?**: `number`

Defined in: [index.d.ts:208](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L208)

---

### queuedMinMessages?

> `optional` **queuedMinMessages?**: `number`

Defined in: [index.d.ts:207](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L207)

---

### readBackoffMax

> **readBackoffMax**: `number`

Defined in: [index.d.ts:228](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L228)

---

### readBackoffMin

> **readBackoffMin**: `number`

Defined in: [index.d.ts:227](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L227)

---

### readBatchTimeout

> **readBatchTimeout**: `number`

Defined in: [index.d.ts:213](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L213)

---

### readLagInterval

> **readLagInterval**: `number`

Defined in: [index.d.ts:216](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L216)

---

### rebalanceTimeout

> **rebalanceTimeout**: `number`

Defined in: [index.d.ts:223](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L223)

---

### retentionTime

> **retentionTime**: `number`

Defined in: [index.d.ts:225](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L225)

---

### sasl

> **sasl**: [`SASLConfig`](SASLConfig.md)

Defined in: [index.d.ts:235](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L235)

---

### sessionTimeout

> **sessionTimeout**: `number`

Defined in: [index.d.ts:222](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L222)

---

### socketKeepAlive?

> `optional` **socketKeepAlive?**: `boolean`

Defined in: [index.d.ts:233](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L233)

---

### startOffset

> **startOffset**: [`START_OFFSETS`](../enumerations/START_OFFSETS.md)

Defined in: [index.d.ts:226](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L226)

---

### tls

> **tls**: [`TLSConfig`](TLSConfig.md)

Defined in: [index.d.ts:236](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L236)

---

### topic

> **topic**: `string`

Defined in: [index.d.ts:205](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L205)

---

### watchPartitionChanges

> **watchPartitionChanges**: `boolean`

Defined in: [index.d.ts:221](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L221)
