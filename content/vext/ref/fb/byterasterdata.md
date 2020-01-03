---
title: ByteRasterData
---
### Base Classes

[RasterQuadtreeData](RasterQuadtreeData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                               | Description                                                                                                         |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| ByteRasterData()                                                          | Create a new instance of this container type.                                                                       |
| ByteRasterData(ByteRasterData other)                                      | Create a reference copy of an instance of the same type.                                                            |
| ByteRasterData([RasterQuadtreeData](RasterQuadtreeData) other)            | Upcast an instance of type [RasterQuadtreeData](RasterQuadtreeData) to [ByteRasterData](ByteRasterData).            |
| ByteRasterData([Asset](Asset) other)                                      | Upcast an instance of type [Asset](Asset) to [ByteRasterData](ByteRasterData).                                      |
| ByteRasterData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [ByteRasterData](ByteRasterData). |

## Methods

| Type                             | Name            | Parameters                                     |
| -------------------------------- | --------------- | ---------------------------------------------- |
| [ByteRasterData](ByteRasterData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [ByteRasterData](ByteRasterData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |