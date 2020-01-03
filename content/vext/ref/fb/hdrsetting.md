---
title: HdrSetting
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                           | Description                                                                                                 |
| --------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- |
| HdrSetting()                                                          | Create a new instance of this container type.                                                               |
| HdrSetting(HdrSetting other)                                          | Create a reference copy of an instance of the same type.                                                    |
| HdrSetting([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [HdrSetting](HdrSetting). |

## Properties

| Name                      | Type                     | Description |
| ------------------------- | ------------------------ | ----------- |
| windowMinTop              | number                   |             |
| windowMinBottom           | number                   |             |
| windowTopMinReleaseTime   | number                   |             |
| windowTopMaxReleaseTime   | number                   |             |
| windowTopAttackTime       | number                   |             |
| windowBottomReleaseTime   | number                   |             |
| windowTopReleaseTimeCurve | [AudioCurve](AudioCurve) |             |
| dischargeFactor           | number                   |             |
| maxAllowedEnergy          | number                   |             |
| windowBottomAttackTime    | number                   |             |
| windowSize                | number                   |             |
| compressFactor            | number                   |             |
| headroom                  | number                   |             |
| allowedOvershoot          | number                   |             |

## Methods

| Type                     | Name            | Parameters                                     |
| ------------------------ | --------------- | ---------------------------------------------- |
| [HdrSetting](HdrSetting) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [HdrSetting](HdrSetting) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |