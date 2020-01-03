---
title: Vec4RecordingData
---
### Base Classes

[PropertyRecordingData](PropertyRecordingData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                  | Description                                                                                                               |
| ---------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- |
| Vec4RecordingData()                                                          | Create a new instance of this container type.                                                                             |
| Vec4RecordingData(Vec4RecordingData other)                                   | Create a reference copy of an instance of the same type.                                                                  |
| Vec4RecordingData([PropertyRecordingData](PropertyRecordingData) other)      | Upcast an instance of type [PropertyRecordingData](PropertyRecordingData) to [Vec4RecordingData](Vec4RecordingData).      |
| Vec4RecordingData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [Vec4RecordingData](Vec4RecordingData). |

## Properties

| Name   | Type                                  | Description |
| ------ | ------------------------------------- | ----------- |
| values | [Vec4](/vext/ref/shared/class/vec4)\[\] |             |

## Methods

| Type                                   | Name            | Parameters                                     |
| -------------------------------------- | --------------- | ---------------------------------------------- |
| [Vec4RecordingData](Vec4RecordingData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [Vec4RecordingData](Vec4RecordingData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |