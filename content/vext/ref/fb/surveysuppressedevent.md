---
title: SurveySuppressedEvent
---

Inherits from [MetricEvent](/vext/ref/fb/metricevent)

## Summary

### Constructors

|  |
| --- |
| **[SurveySuppressedEvent](#constructor-0)**() |
| **[SurveySuppressedEvent](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[SurveySuppressedEvent](#constructor-2)**(other: [MetricEvent](/vext/ref/fb/metricevent)) |
| **[SurveySuppressedEvent](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "suppressReason" >}} | string |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "SurveySuppressedEvent" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### SurveySuppressedEvent {#constructor-0}

> **SurveySuppressedEvent**()

Creates a new [SurveySuppressedEvent](/vext/ref/fb/surveysuppressedevent) frostbite instance.

### SurveySuppressedEvent {#constructor-1}

> **SurveySuppressedEvent**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [SurveySuppressedEvent](/vext/ref/fb/surveysuppressedevent) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### SurveySuppressedEvent {#constructor-2}

> **SurveySuppressedEvent**(other: [MetricEvent](/vext/ref/fb/metricevent))

Casts an instance of type [MetricEvent](/vext/ref/fb/metricevent) to [SurveySuppressedEvent](/vext/ref/fb/surveysuppressedevent). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [MetricEvent](/vext/ref/fb/metricevent) | The instance to cast to [SurveySuppressedEvent](/vext/ref/fb/surveysuppressedevent). |

### SurveySuppressedEvent {#constructor-3}

> **SurveySuppressedEvent**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [SurveySuppressedEvent](/vext/ref/fb/surveysuppressedevent). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [SurveySuppressedEvent](/vext/ref/fb/surveysuppressedevent). |

## Properties

### {{% prop-heading "suppressReason" %}}

> **string**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [SurveySuppressedEvent](/vext/ref/fb/surveysuppressedevent) type.

