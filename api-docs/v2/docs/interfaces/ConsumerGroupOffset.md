[**xk6-kafka**](../README.md)

---

# Interface: ConsumerGroupOffset

Defined in: [index.d.ts:322](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L322)

One topic-partition offset captured for a consumer group.

## Properties

### offset

> **offset**: `number`

Defined in: [index.d.ts:326](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L326)

Loses integer precision above 2^53; only a concern for extremely large offsets.

---

### partition

> **partition**: `number`

Defined in: [index.d.ts:324](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L324)

---

### topic

> **topic**: `string`

Defined in: [index.d.ts:323](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L323)
