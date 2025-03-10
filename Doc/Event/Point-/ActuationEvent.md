[Index](../../index.md) > [Event](../Event.md) > [PointEvent](PointEvent.md) > [ActuationEvent](#)
# ActuationEvent

**Display name:** Actuation event<br />
**DTMI:** dtmi:org:w3id:rec:ActuationEvent;1

---

## Relationships

|Name|Display name|Description|Multiplicity|Target|Properties|Writable|
|-|-|-|-|-|-|-|
|targetPoint|**en**: target point|**en**: The brick:Point(s) (e.g., brick:Commands, brick:Setpoints, or brick:Parameters) that the actuation will target/execute.|0-Infinity|[Point](../../Point/Point.md)||True|

---

## Properties

|Name|Display name|Description|Schema|Writable|
|-|-|-|-|-|
|value|**en**: value|**en**: The command message/payload of this actuation event.|string|True|
### Inherited Properties
* **[Event](../Event.md):** customProperties, customTags, end, identifiers, name, start, timestamp

---

## Target Of
### General
* [Point](../../Point/Point.md).isPointOf
* [Agent](../../Agent/Agent.md).owns
* [Space](../../Space/Space.md).isLocationOf
* [Equipment](../../Asset/Equipment/Equipment.md).feeds
* [Equipment](../../Asset/Equipment/Equipment.md).isFedBy
* [Architecture](../../Space/Architecture/Architecture.md).isFedBy
* [Document](../../Information/Document/Document.md).documentTopic
* [Document](../../Information/Document/Document.md).url
* [Lease](../Lease.md).leaseOf
* [PointOfInterest](../../Information/PointOfInterest.md).objectOfInterest
* [Portfolio](../../Collection/Portfolio.md).includes
* [ServiceObject](../../Information/ServiceObject/ServiceObject.md).relatedTo
* [Meter](../../Asset/Equipment/Meter/Meter.md).meters
