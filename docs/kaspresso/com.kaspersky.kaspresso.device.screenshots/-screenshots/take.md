[kaspresso](../../index.md) / [com.kaspersky.kaspresso.device.screenshots](../index.md) / [Screenshots](index.md) / [take](./take.md)

# take

`abstract fun take(tag: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)

Takes screenshot if it is possible.

Required Permissions: WRITE_EXTERNAL_STORAGE.

### Parameters

`tag` - a unique tag to further identify the screenshot. Must match [a-zA-Z0-9_-](#)+.