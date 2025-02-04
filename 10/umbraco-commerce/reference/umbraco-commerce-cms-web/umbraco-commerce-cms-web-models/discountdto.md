---
title: DiscountDto
description: API reference for DiscountDto in Umbraco Commerce
---
## DiscountDto

```csharp
public class DiscountDto : DiscountBasicDto
```

**Inheritance**

* class [DiscountBasicDto](discountbasicdto.md)

**Namespace**
* [Umbraco.Commerce.Cms.Web.Models](README.md)

### Constructors

#### DiscountDto

The default constructor.

```csharp
public DiscountDto()
```


### Properties

#### Codes

```csharp
public List<DiscountCodeDto> Codes { get; set; }
```


---

#### ExpiryDate

```csharp
public DateTime? ExpiryDate { get; set; }
```


---

#### IsActive

```csharp
public bool IsActive { get; set; }
```


---

#### Rewards

```csharp
public List<DiscountRewardConfigDto> Rewards { get; set; }
```


---

#### Rules

```csharp
public DiscountRuleConfigDto Rules { get; set; }
```


---

#### StartDate

```csharp
public DateTime? StartDate { get; set; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.Web.dll -->
