---
title: Currency
description: API reference for Currency in Umbraco Commerce
---
## Currency

```csharp
public class Currency : CurrencyReadOnly, IHasWrtiableAllowedCountries<Currency>
```

**Inheritance**

* class [CurrencyReadOnly](currencyreadonly.md)
* interface [IHasWrtiableAllowedCountries&lt;TAggregate&gt;](ihaswrtiableallowedcountries-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Methods

#### Create (1 of 2)

```csharp
public static Currency Create(IUnitOfWork uow, Guid storeId, string code, string name, 
    string cultureName)
```

---

#### Create (2 of 2)

```csharp
public static Currency Create(IUnitOfWork uow, Guid id, Guid storeId, string code, string name, 
    string cultureName)
```


---

#### AllowInCountry (1 of 2)

```csharp
public Currency AllowInCountry(CountryReadOnly country)
```

---

#### AllowInCountry (2 of 2)

```csharp
public Currency AllowInCountry(Guid countryId)
```


---

#### DisallowInCountry (1 of 2)

```csharp
public Currency DisallowInCountry(CountryReadOnly country)
```

---

#### DisallowInCountry (2 of 2)

```csharp
public Currency DisallowInCountry(Guid countryId)
```


---

#### SetCode

```csharp
public Currency SetCode(string code)
```


---

#### SetCulture

```csharp
public Currency SetCulture(string cultureName)
```


---

#### SetCustomFormatTemplate

```csharp
public Currency SetCustomFormatTemplate(string formatTemplate)
```


---

#### SetName

```csharp
public Currency SetName(string name)
```


---

#### SetSortOrder

```csharp
public Currency SetSortOrder(int sortOrder)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
