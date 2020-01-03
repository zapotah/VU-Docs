---
title: EffectManagerSettings
---
### Base Classes

[SystemSettings](SystemSettings)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                      | Description                                                                                                                       |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| EffectManagerSettings()                                                          | Create a new instance of this container type.                                                                                     |
| EffectManagerSettings(EffectManagerSettings other)                               | Create a reference copy of an instance of the same type.                                                                          |
| EffectManagerSettings([SystemSettings](SystemSettings) other)                    | Upcast an instance of type [SystemSettings](SystemSettings) to [EffectManagerSettings](EffectManagerSettings).                    |
| EffectManagerSettings([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [EffectManagerSettings](EffectManagerSettings). |

## Properties

| Name                          | Type   | Description |
| ----------------------------- | ------ | ----------- |
| maxNewEffectsPerFrameCount    | number |             |
| sizeToGrowNewEffectsContainer | number |             |
| effectQuality                 | number |             |

## Methods

| Type                                           | Name            | Parameters                                     |
| ---------------------------------------------- | --------------- | ---------------------------------------------- |
| [EffectManagerSettings](EffectManagerSettings) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [EffectManagerSettings](EffectManagerSettings) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |