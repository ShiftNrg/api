**Polkadot JS API**

> [README](../README.md) / [Globals](../globals.md) / ["packages/types/src/ethereum/AccountId"](../modules/_packages_types_src_ethereum_accountid_.md) / AccountId

# Class: AccountId

**`name`** EthereumAccountId

**`description`** 
A wrapper around an Ethereum-compatible AccountId. Since we are dealing with
underlying addresses (20 bytes in length), we extend from U8aFixed which is
just a Uint8Array wrapper with a fixed length.

## Hierarchy

* [U8aFixed](_packages_types_src_codec_u8afixed_.u8afixed.md)

  ↳ **AccountId**

## Implements

* [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)

## Indexable

▪ [index: number]: number

**`name`** EthereumAccountId

**`description`** 
A wrapper around an Ethereum-compatible AccountId. Since we are dealing with
underlying addresses (20 bytes in length), we extend from U8aFixed which is
just a Uint8Array wrapper with a fixed length.

## Index

### Constructors

* [constructor](_packages_types_src_ethereum_accountid_.accountid.md#constructor)

### Properties

* [registry](_packages_types_src_ethereum_accountid_.accountid.md#registry)

### Accessors

* [encodedLength](_packages_types_src_ethereum_accountid_.accountid.md#encodedlength)
* [hash](_packages_types_src_ethereum_accountid_.accountid.md#hash)
* [isAscii](_packages_types_src_ethereum_accountid_.accountid.md#isascii)
* [isEmpty](_packages_types_src_ethereum_accountid_.accountid.md#isempty)
* [isUtf8](_packages_types_src_ethereum_accountid_.accountid.md#isutf8)
* [length](_packages_types_src_ethereum_accountid_.accountid.md#length)

### Methods

* [bitLength](_packages_types_src_ethereum_accountid_.accountid.md#bitlength)
* [eq](_packages_types_src_ethereum_accountid_.accountid.md#eq)
* [subarray](_packages_types_src_ethereum_accountid_.accountid.md#subarray)
* [toHex](_packages_types_src_ethereum_accountid_.accountid.md#tohex)
* [toHuman](_packages_types_src_ethereum_accountid_.accountid.md#tohuman)
* [toJSON](_packages_types_src_ethereum_accountid_.accountid.md#tojson)
* [toRawType](_packages_types_src_ethereum_accountid_.accountid.md#torawtype)
* [toString](_packages_types_src_ethereum_accountid_.accountid.md#tostring)
* [toU8a](_packages_types_src_ethereum_accountid_.accountid.md#tou8a)
* [toUtf8](_packages_types_src_ethereum_accountid_.accountid.md#toutf8)
* [encode](_packages_types_src_ethereum_accountid_.accountid.md#encode)
* [with](_packages_types_src_ethereum_accountid_.accountid.md#with)

## Constructors

### constructor

\+ **new AccountId**(`registry`: [Registry](../interfaces/_packages_types_src_types_registry_.registry.md), `value`: [AnyU8a](../modules/_packages_types_src_types_helpers_.md#anyu8a)): [AccountId](_packages_types_src_ethereum_accountid_.accountid.md)

*Overrides [U8aFixed](_packages_types_src_codec_u8afixed_.u8afixed.md).[constructor](_packages_types_src_codec_u8afixed_.u8afixed.md#constructor)*

*Defined in [packages/types/src/ethereum/AccountId.ts:31](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/ethereum/AccountId.ts#L31)*

#### Parameters:

Name | Type | Default value |
------ | ------ | ------ |
`registry` | [Registry](../interfaces/_packages_types_src_types_registry_.registry.md) | - |
`value` | [AnyU8a](../modules/_packages_types_src_types_helpers_.md#anyu8a) | new Uint8Array() |

**Returns:** [AccountId](_packages_types_src_ethereum_accountid_.accountid.md)

## Properties

### registry

• `Readonly` **registry**: [Registry](../interfaces/_packages_types_src_types_registry_.registry.md)

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md).[registry](../interfaces/_packages_types_src_types_interfaces_.iu8a.md#registry)*

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[registry](_packages_types_src_codec_raw_.raw.md#registry)*

*Defined in [packages/types/src/codec/Raw.ts:28](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L28)*

## Accessors

### encodedLength

• get **encodedLength**(): number

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[encodedLength](_packages_types_src_codec_raw_.raw.md#encodedlength)*

*Defined in [packages/types/src/codec/Raw.ts:39](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L39)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** number

___

### hash

• get **hash**(): H256

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[hash](_packages_types_src_codec_raw_.raw.md#hash)*

*Defined in [packages/types/src/codec/Raw.ts:46](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L46)*

**`description`** returns a hash of the contents

**Returns:** H256

___

### isAscii

• get **isAscii**(): boolean

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[isAscii](_packages_types_src_codec_raw_.raw.md#isascii)*

*Defined in [packages/types/src/codec/Raw.ts:53](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L53)*

**`description`** Returns true if the wrapped value contains only ASCII printable characters

**Returns:** boolean

___

### isEmpty

• get **isEmpty**(): boolean

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[isEmpty](_packages_types_src_codec_raw_.raw.md#isempty)*

*Defined in [packages/types/src/codec/Raw.ts:60](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L60)*

**`description`** Returns true if the type wraps an empty/default all-0 value

**Returns:** boolean

___

### isUtf8

• get **isUtf8**(): boolean

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[isUtf8](_packages_types_src_codec_raw_.raw.md#isutf8)*

*Defined in [packages/types/src/codec/Raw.ts:67](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L67)*

**`description`** Returns true if the wrapped value contains only utf8 characters

**Returns:** boolean

___

### length

• get **length**(): number

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[length](_packages_types_src_codec_raw_.raw.md#length)*

*Overrides [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md).[length](../interfaces/_packages_types_src_types_interfaces_.iu8a.md#length)*

*Defined in [packages/types/src/codec/Raw.ts:74](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L74)*

**`description`** The length of the value

**Returns:** number

## Methods

### bitLength

▸ **bitLength**(): number

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)*

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[bitLength](_packages_types_src_codec_raw_.raw.md#bitlength)*

*Defined in [packages/types/src/codec/Raw.ts:82](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L82)*

**`description`** Returns the number of bits in the value

**Returns:** number

___

### eq

▸ **eq**(`other?`: unknown): boolean

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)*

*Overrides [Raw](_packages_types_src_codec_raw_.raw.md).[eq](_packages_types_src_codec_raw_.raw.md#eq)*

*Defined in [packages/types/src/ethereum/AccountId.ts:43](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/ethereum/AccountId.ts#L43)*

**`description`** Compares the value of the input to see if there is a match

#### Parameters:

Name | Type |
------ | ------ |
`other?` | unknown |

**Returns:** boolean

___

### subarray

▸ **subarray**(`begin`: number, `end?`: undefined \| number): [Uint8Array](_packages_types_src_codec_raw_.raw.md#uint8array)

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[subarray](_packages_types_src_codec_raw_.raw.md#subarray)*

*Overrides [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md).[subarray](../interfaces/_packages_types_src_types_interfaces_.iu8a.md#subarray)*

*Defined in [packages/types/src/codec/Raw.ts:103](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L103)*

**`description`** Create a new subarray from the actual buffer. This is needed for compat reasons since a new Uint8Array gets returned here

#### Parameters:

Name | Type | Description |
------ | ------ | ------ |
`begin` | number | The position to start at |
`end?` | undefined \| number | The position to end at  |

**Returns:** [Uint8Array](_packages_types_src_codec_raw_.raw.md#uint8array)

___

### toHex

▸ **toHex**(): string

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[toHex](_packages_types_src_codec_raw_.raw.md#tohex)*

*Defined in [packages/types/src/codec/Raw.ts:110](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L110)*

**`description`** Returns a hex string representation of the value

**Returns:** string

___

### toHuman

▸ **toHuman**(): string

*Overrides [Raw](_packages_types_src_codec_raw_.raw.md).[toHuman](_packages_types_src_codec_raw_.raw.md#tohuman)*

*Defined in [packages/types/src/ethereum/AccountId.ts:50](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/ethereum/AccountId.ts#L50)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

**Returns:** string

___

### toJSON

▸ **toJSON**(): string

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)*

*Overrides [Raw](_packages_types_src_codec_raw_.raw.md).[toJSON](_packages_types_src_codec_raw_.raw.md#tojson)*

*Defined in [packages/types/src/ethereum/AccountId.ts:57](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/ethereum/AccountId.ts#L57)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** string

___

### toRawType

▸ **toRawType**(): string

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)*

*Overrides [U8aFixed](_packages_types_src_codec_u8afixed_.u8afixed.md).[toRawType](_packages_types_src_codec_u8afixed_.u8afixed.md#torawtype)*

*Defined in [packages/types/src/ethereum/AccountId.ts:71](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/ethereum/AccountId.ts#L71)*

**`description`** Returns the base runtime type name for this instance

**Returns:** string

___

### toString

▸ **toString**(): string

*Implementation of [IU8a](../interfaces/_packages_types_src_types_interfaces_.iu8a.md)*

*Overrides [Raw](_packages_types_src_codec_raw_.raw.md).[toString](_packages_types_src_codec_raw_.raw.md#tostring)*

*Defined in [packages/types/src/ethereum/AccountId.ts:64](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/ethereum/AccountId.ts#L64)*

**`description`** Returns the string representation of the value

**Returns:** string

___

### toU8a

▸ **toU8a**(`isBare?`: undefined \| false \| true): [Uint8Array](_packages_types_src_codec_raw_.raw.md#uint8array)

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[toU8a](_packages_types_src_codec_raw_.raw.md#tou8a)*

*Defined in [packages/types/src/codec/Raw.ts:149](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L149)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

#### Parameters:

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | undefined \| false \| true | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** [Uint8Array](_packages_types_src_codec_raw_.raw.md#uint8array)

___

### toUtf8

▸ **toUtf8**(): string

*Inherited from [Raw](_packages_types_src_codec_raw_.raw.md).[toUtf8](_packages_types_src_codec_raw_.raw.md#toutf8)*

*Defined in [packages/types/src/codec/Raw.ts:156](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/Raw.ts#L156)*

**`description`** Returns the wrapped data as a UTF-8 string

**Returns:** string

___

### encode

▸ `Static`**encode**(`value`: [Uint8Array](_packages_types_src_codec_raw_.raw.md#uint8array)): string

*Defined in [packages/types/src/ethereum/AccountId.ts:36](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/ethereum/AccountId.ts#L36)*

#### Parameters:

Name | Type |
------ | ------ |
`value` | [Uint8Array](_packages_types_src_codec_raw_.raw.md#uint8array) |

**Returns:** string

___

### with

▸ `Static`**with**(`bitLength`: [BitLength](../modules/_packages_types_src_codec_u8afixed_.md#bitlength), `typeName?`: undefined \| string): [Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)\<[U8aFixed](_packages_types_src_codec_u8afixed_.u8afixed.md)>

*Inherited from [U8aFixed](_packages_types_src_codec_u8afixed_.u8afixed.md).[with](_packages_types_src_codec_u8afixed_.u8afixed.md#with)*

*Defined in [packages/types/src/codec/U8aFixed.ts:49](https://github.com/polkadot-js/api/blob/33c161f87/packages/types/src/codec/U8aFixed.ts#L49)*

#### Parameters:

Name | Type |
------ | ------ |
`bitLength` | [BitLength](../modules/_packages_types_src_codec_u8afixed_.md#bitlength) |
`typeName?` | undefined \| string |

**Returns:** [Constructor](../interfaces/_packages_types_src_types_codec_.constructor.md)\<[U8aFixed](_packages_types_src_codec_u8afixed_.u8afixed.md)>