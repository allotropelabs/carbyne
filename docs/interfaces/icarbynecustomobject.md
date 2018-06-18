[carbyne-db](../README.md) > [ICarbyneCustomObject](../interfaces/icarbynecustomobject.md)

# Interface: ICarbyneCustomObject

A custom object. See [Carbyne.registerCustomObject](../classes/carbyne.md#registercustomobject).

## Hierarchy

**ICarbyneCustomObject**

## Implemented by

* [CarbyneBlob](../classes/carbyneblob.md)

## Index

### Properties

* [_id](icarbynecustomobject.md#_id)

### Methods

* [serialize](icarbynecustomobject.md#serialize)

---

## Properties

<a id="_id"></a>

###  _id

**● _id**: * `string` &#124; `undefined`
*

*Defined in [lib/types.ts:276](https://github.com/allotropelabs/carbyne/blob/22aec63/lib/types.ts#L276)*

___

## Methods

<a id="serialize"></a>

###  serialize

▸ **serialize**(): `Promise`<`any`>

*Defined in [lib/types.ts:282](https://github.com/allotropelabs/carbyne/blob/22aec63/lib/types.ts#L282)*

Serialize this custom object, return an object that can be passed to MessagePack.

**Returns:** `Promise`<`any`>

___
