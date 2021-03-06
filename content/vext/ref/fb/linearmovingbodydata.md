---
title: LinearMovingBodyData
---

Inherits from [MovingBodyData](/vext/ref/fb/movingbodydata)

## Summary

### Constructors

|  |
| --- |
| **[LinearMovingBodyData](#constructor-0)**() |
| **[LinearMovingBodyData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[LinearMovingBodyData](#constructor-2)**(other: [MovingBodyData](/vext/ref/fb/movingbodydata)) |
| **[LinearMovingBodyData](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "axis" >}} | [Vec3](/vext/ref/shared/type/vec3) |
| {{< prop "start" >}} | [EndPointData](/vext/ref/fb/endpointdata) |
| {{< prop "endValue" >}} | [EndPointData](/vext/ref/fb/endpointdata) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "LinearMovingBodyData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### LinearMovingBodyData {#constructor-0}

> **LinearMovingBodyData**()

Creates a new [LinearMovingBodyData](/vext/ref/fb/linearmovingbodydata) frostbite instance.

### LinearMovingBodyData {#constructor-1}

> **LinearMovingBodyData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [LinearMovingBodyData](/vext/ref/fb/linearmovingbodydata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### LinearMovingBodyData {#constructor-2}

> **LinearMovingBodyData**(other: [MovingBodyData](/vext/ref/fb/movingbodydata))

Casts an instance of type [MovingBodyData](/vext/ref/fb/movingbodydata) to [LinearMovingBodyData](/vext/ref/fb/linearmovingbodydata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [MovingBodyData](/vext/ref/fb/movingbodydata) | The instance to cast to [LinearMovingBodyData](/vext/ref/fb/linearmovingbodydata). |

### LinearMovingBodyData {#constructor-3}

> **LinearMovingBodyData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [LinearMovingBodyData](/vext/ref/fb/linearmovingbodydata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [LinearMovingBodyData](/vext/ref/fb/linearmovingbodydata). |

## Properties

### {{% prop-heading "axis" %}}

> **[Vec3](/vext/ref/shared/type/vec3)**

### {{% prop-heading "start" %}}

> **[EndPointData](/vext/ref/fb/endpointdata)**

### {{% prop-heading "endValue" %}}

> **[EndPointData](/vext/ref/fb/endpointdata)**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [LinearMovingBodyData](/vext/ref/fb/linearmovingbodydata) type.

