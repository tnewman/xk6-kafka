[**xk6-kafka**](../README.md)

---

# Interface: ConsumeConfig

Defined in: [index.d.ts:240](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L240)

Configuration for Consume method.

## Properties

### expectTimeout

> **expectTimeout**: `boolean`

Defined in: [index.d.ts:251](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L251)

If true, return whatever messages have been collected when maxWait is
passed.

---

### limit?

> `optional` **limit?**: `number`

Defined in: [index.d.ts:242](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L242)

collect this many messages before returning.

---

### maxMessages?

> `optional` **maxMessages?**: `number`

Defined in: [index.d.ts:244](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L244)

preferred v2 alias for limit.

---

### nanoPrecision

> **nanoPrecision**: `boolean`

Defined in: [index.d.ts:246](https://github.com/mostafa/xk6-kafka/blob/main/api-docs/v2/index.d.ts#L246)

If true, returned message RFC3339 timestamps carry nanosecond precision.
