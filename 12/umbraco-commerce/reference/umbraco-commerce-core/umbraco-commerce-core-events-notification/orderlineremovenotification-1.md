---
title: OrderLineRemoveNotification<TEntity>
description: API reference for OrderLineRemoveNotification<TEntity> in Umbraco Commerce
---
## OrderLineRemoveNotification&lt;TEntity&gt;

```csharp
public class OrderLineRemoveNotification<TEntity> : OrderNotificationEventBase<TEntity>, 
    IHasEventKey
    where TEntity : OrderReadOnly
```

**Inheritance**

* class [OrderNotificationEventBase&lt;TOrder&gt;](ordernotificationeventbase-1.md)
* interface [IHasEventKey](../../umbraco-commerce-common/umbraco-commerce-common-events/ihaseventkey.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### OrderLineRemoveNotification&lt;TEntity&gt;

```csharp
public OrderLineRemoveNotification(TEntity order, OrderLineReadOnly orderLine)
```


### Properties

#### Key

```csharp
public string Key { get; }
```


---

#### OrderLine

```csharp
public OrderLineReadOnly OrderLine { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->