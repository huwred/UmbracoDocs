---
title: ValidatePaymentMethodTaxClassChange
description: API reference for ValidatePaymentMethodTaxClassChange in Umbraco Commerce
---
## ValidatePaymentMethodTaxClassChange

```csharp
public class ValidatePaymentMethodTaxClassChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidatePaymentMethodTaxClassChange

```csharp
public ValidatePaymentMethodTaxClassChange(PaymentMethodReadOnly paymentMethod, 
    ChangingValue<Guid?> taxClassId)
```


### Properties

#### PaymentMethod

```csharp
public PaymentMethodReadOnly PaymentMethod { get; }
```


---

#### TaxClassId

```csharp
public ChangingValue<Guid?> TaxClassId { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
