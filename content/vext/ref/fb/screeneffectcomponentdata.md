---
title: ScreenEffectComponentData
---
### Base Classes

[ComponentData](ComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                          | Description                                                                                                                               |
| ------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- |
| ScreenEffectComponentData()                                                          | Create a new instance of this container type.                                                                                             |
| ScreenEffectComponentData(ScreenEffectComponentData other)                           | Create a reference copy of an instance of the same type.                                                                                  |
| ScreenEffectComponentData([ComponentData](ComponentData) other)                      | Upcast an instance of type [ComponentData](ComponentData) to [ScreenEffectComponentData](ScreenEffectComponentData).                      |
| ScreenEffectComponentData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [ScreenEffectComponentData](ScreenEffectComponentData).                    |
| ScreenEffectComponentData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [ScreenEffectComponentData](ScreenEffectComponentData).              |
| ScreenEffectComponentData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [ScreenEffectComponentData](ScreenEffectComponentData). |

## Properties

| Name               | Type                                             | Description |
| ------------------ | ------------------------------------------------ | ----------- |
| screenEffectParams | [Vec4](/vext/ref/shared/class/vec4)                |             |
| frameType          | [ScreenEffectFrameType](ScreenEffectFrameType)   |             |
| shader             | [SurfaceShaderBaseAsset](SurfaceShaderBaseAsset) |             |
| frameWidth         | number                                           |             |
| outerFrameOpacity  | number                                           |             |
| innerFrameOpacity  | number                                           |             |
| angle              | number                                           |             |
| realm              | [Realm](Realm)                                   |             |

## Methods

| Type                                                   | Name            | Parameters                                     |
| ------------------------------------------------------ | --------------- | ---------------------------------------------- |
| [ScreenEffectComponentData](ScreenEffectComponentData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [ScreenEffectComponentData](ScreenEffectComponentData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |