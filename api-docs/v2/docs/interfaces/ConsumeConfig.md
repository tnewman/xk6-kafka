[**xk6-kafka**](../README.md)

---

# Interface: ConsumeConfig

Defined in: [index.d.ts:242](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L242)

Configuration for Consume method.

## Properties

### expectTimeout

> **expectTimeout**: `boolean`

Defined in: [index.d.ts:253](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L253)

If true, return whatever messages have been collected when maxWait is
passed.

---

### limit?

> `optional` **limit?**: `number`

Defined in: [index.d.ts:244](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L244)

collect this many messages before returning.

---

### maxMessages?

> `optional` **maxMessages?**: `number`

Defined in: [index.d.ts:246](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L246)

preferred v2 alias for limit.

---

### nanoPrecision

> **nanoPrecision**: `boolean`

Defined in: [index.d.ts:248](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L248)

If true, returned message RFC3339 timestamps carry nanosecond precision.
