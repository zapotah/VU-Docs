---
title: MeshMaterialVariation
---
### Base Classes

[DataContainer](/vext/ref/shared/class/datacontainer)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                      | Description                                                                                                                       |
| -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| MeshMaterialVariation()                                                          | Create a new instance of this container type.                                                                                     |
| MeshMaterialVariation(MeshMaterialVariation other)                               | Create a reference copy of an instance of the same type.                                                                          |
| MeshMaterialVariation([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [MeshMaterialVariation](MeshMaterialVariation). |

## Properties

| Name   | Type                                                               | Description |
| ------ | ------------------------------------------------------------------ | ----------- |
| shader | [SurfaceShaderInstanceDataStruct](SurfaceShaderInstanceDataStruct) |             |

## Methods

| Type                                           | Name            | Parameters                                     |
| ---------------------------------------------- | --------------- | ---------------------------------------------- |
| [MeshMaterialVariation](MeshMaterialVariation) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [MeshMaterialVariation](MeshMaterialVariation) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |