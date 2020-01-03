---
title: SurroundingGeometryEntityData
---
### Base Classes

[GameEntityData](GameEntityData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                              | Description                                                                                                                                       |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| SurroundingGeometryEntityData()                                                          | Create a new instance of this container type.                                                                                                     |
| SurroundingGeometryEntityData(SurroundingGeometryEntityData other)                       | Create a reference copy of an instance of the same type.                                                                                          |
| SurroundingGeometryEntityData([GameEntityData](GameEntityData) other)                    | Upcast an instance of type [GameEntityData](GameEntityData) to [SurroundingGeometryEntityData](SurroundingGeometryEntityData).                    |
| SurroundingGeometryEntityData([SpatialEntityData](SpatialEntityData) other)              | Upcast an instance of type [SpatialEntityData](SpatialEntityData) to [SurroundingGeometryEntityData](SurroundingGeometryEntityData).              |
| SurroundingGeometryEntityData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [SurroundingGeometryEntityData](SurroundingGeometryEntityData).                            |
| SurroundingGeometryEntityData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [SurroundingGeometryEntityData](SurroundingGeometryEntityData).                    |
| SurroundingGeometryEntityData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [SurroundingGeometryEntityData](SurroundingGeometryEntityData).              |
| SurroundingGeometryEntityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [SurroundingGeometryEntityData](SurroundingGeometryEntityData). |

## Properties

| Name               | Type                                                       | Description |
| ------------------ | ---------------------------------------------------------- | ----------- |
| allowedVehicleList | [AllowedVehiclesData](AllowedVehiclesData)                 |             |
| combatArea         | [CombatAreaTriggerEntityData](CombatAreaTriggerEntityData) |             |
| combatAreaIndex    | number                                                     |             |

## Methods

| Type                                                           | Name            | Parameters                                     |
| -------------------------------------------------------------- | --------------- | ---------------------------------------------- |
| [SurroundingGeometryEntityData](SurroundingGeometryEntityData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [SurroundingGeometryEntityData](SurroundingGeometryEntityData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |