---
title: OrderPaymentMethodChangeNotificationBase<TEntity>
description: API reference for OrderPaymentMethodChangeNotificationBase<TEntity> in Umbraco Commerce
---
## OrderPaymentMethodChangeNotificationBase&lt;TEntity&gt;

```csharp
public abstract class OrderPaymentMethodChangeNotificationBase<TEntity> : 
    OrderNotificationEventBase<TEntity>
    where TEntity : OrderReadOnly
```

**Inheritance**

* class [OrderNotificationEventBase&lt;TOrder&gt;](ordernotificationeventbase-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Notification](README.md)

### Constructors

#### OrderPaymentMethodChangeNotificationBase&lt;TEntity&gt;

```csharp
public OrderPaymentMethodChangeNotificationBase(TEntity order, ChangingValue<Guid?> paymentMethodId)
```


### Properties

#### PaymentMethodId

```csharp
public ChangingValue<Guid?> PaymentMethodId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->