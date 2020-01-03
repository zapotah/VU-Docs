---
title: UILeaderboardCompData
---
### Base Classes

[UIComponentData](UIComponentData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                      | Description                                                                                                                       |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| UILeaderboardCompData()                                                          | Create a new instance of this container type.                                                                                     |
| UILeaderboardCompData(UILeaderboardCompData other)                               | Create a reference copy of an instance of the same type.                                                                          |
| UILeaderboardCompData([UIComponentData](UIComponentData) other)                  | Upcast an instance of type [UIComponentData](UIComponentData) to [UILeaderboardCompData](UILeaderboardCompData).                  |
| UILeaderboardCompData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [UILeaderboardCompData](UILeaderboardCompData).                                      |
| UILeaderboardCompData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [UILeaderboardCompData](UILeaderboardCompData). |

## Methods

| Type                                           | Name            | Parameters                                     |
| ---------------------------------------------- | --------------- | ---------------------------------------------- |
| [UILeaderboardCompData](UILeaderboardCompData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [UILeaderboardCompData](UILeaderboardCompData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |