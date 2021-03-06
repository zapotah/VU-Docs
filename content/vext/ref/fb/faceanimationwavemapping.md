---
title: FaceAnimationWaveMapping
---

## Summary

### Constructors

|  |
| --- |
| **[FaceAnimationWaveMapping](#constructor-0)**() |
| **[FaceAnimationWaveMapping](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "waveNameHash" >}} | int |
| {{< prop "antEnumValue" >}} | int |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [FaceAnimationWaveMapping](/vext/ref/fb/faceanimationwavemapping) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "FaceAnimationWaveMapping" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### FaceAnimationWaveMapping {#constructor-0}

> **FaceAnimationWaveMapping**()

Creates a new [FaceAnimationWaveMapping](/vext/ref/fb/faceanimationwavemapping) frostbite instance.

### FaceAnimationWaveMapping {#constructor-1}

> **FaceAnimationWaveMapping**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [FaceAnimationWaveMapping](/vext/ref/fb/faceanimationwavemapping) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "waveNameHash" %}}

> **int**

### {{% prop-heading "antEnumValue" %}}

> **int**

## Methods

### Clone {#clone}

> **Clone**(): [FaceAnimationWaveMapping](/vext/ref/fb/faceanimationwavemapping)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[FaceAnimationWaveMapping](/vext/ref/fb/faceanimationwavemapping)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [FaceAnimationWaveMapping](/vext/ref/fb/faceanimationwavemapping) type.

