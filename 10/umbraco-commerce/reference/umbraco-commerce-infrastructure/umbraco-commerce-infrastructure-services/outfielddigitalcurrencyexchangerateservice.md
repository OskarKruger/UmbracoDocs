---
title: OutfieldDigitalCurrencyExchangeRateService
description: API reference for OutfieldDigitalCurrencyExchangeRateService in Umbraco Commerce
---
## OutfieldDigitalCurrencyExchangeRateService

```csharp
public class OutfieldDigitalCurrencyExchangeRateService : CurrencyExchangeRateServiceBase
```

**Inheritance**

* class [CurrencyExchangeRateServiceBase](currencyexchangerateservicebase.md)

**Namespace**
* [Umbraco.Commerce.Infrastructure.Services](README.md)

### Constructors

#### OutfieldDigitalCurrencyExchangeRateService

The default constructor.

```csharp
public OutfieldDigitalCurrencyExchangeRateService()
```


### Methods

#### FetchExchangeRate

```csharp
public override decimal FetchExchangeRate(string fromCurrencyIsoCode, string toCurrencyIsoCode, 
    DateTime date)
```


---

#### FetchExchangeRates

```csharp
public override Dictionary<string, Dictionary<string, decimal>> FetchExchangeRates(
    string fromCurrencyIsoCode, string[] toCurrencyIsoCodes, DateTime dateFrom, DateTime dateTo)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Infrastructure.dll -->
