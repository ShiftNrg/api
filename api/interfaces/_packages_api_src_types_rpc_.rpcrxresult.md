[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["packages/api/src/types/rpc"](../modules/_packages_api_src_types_rpc_.md) › [RpcRxResult](_packages_api_src_types_rpc_.rpcrxresult.md)

# Interface: RpcRxResult ‹**F**›

## Type parameters

▪ **F**: *AnyFunction*

## Hierarchy

* [RxResult](_packages_api_src_types_base_.rxresult.md)‹F›

  ↳ **RpcRxResult**

## Callable

▸ (...`args`: Parameters‹F›): *Observable‹[ObsInnerType](../modules/_packages_api_src_types_base_.md#obsinnertype)‹ReturnType‹F›››*

*Defined in [packages/api/src/types/base.ts:52](https://github.com/polkadot-js/api/blob/4596e434d/packages/api/src/types/base.ts#L52)*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | Parameters‹F› |

**Returns:** *Observable‹[ObsInnerType](../modules/_packages_api_src_types_base_.md#obsinnertype)‹ReturnType‹F›››*

▸ ‹**T**›(...`args`: Parameters‹F›): *Observable‹T›*

*Defined in [packages/api/src/types/base.ts:53](https://github.com/polkadot-js/api/blob/4596e434d/packages/api/src/types/base.ts#L53)*

**Type parameters:**

▪ **T**

**Parameters:**

Name | Type |
------ | ------ |
`...args` | Parameters‹F› |

**Returns:** *Observable‹T›*

## Index

### Methods

* [raw](_packages_api_src_types_rpc_.rpcrxresult.md#raw)

## Methods

###  raw

▸ **raw**(...`args`: Parameters‹F›): *Observable‹Uint8Array & Codec›*

*Defined in [packages/api/src/types/rpc.ts:14](https://github.com/polkadot-js/api/blob/4596e434d/packages/api/src/types/rpc.ts#L14)*

**Parameters:**

Name | Type |
------ | ------ |
`...args` | Parameters‹F› |

**Returns:** *Observable‹Uint8Array & Codec›*