---
title: ValidateDiscountAliasChange
description: API reference for ValidateDiscountAliasChange in Umbraco Commerce
---
## ValidateDiscountAliasChange

```csharp
public class ValidateDiscountAliasChange : ValidationEventBase
```

**Inheritance**

* class [ValidationEventBase](../../umbraco-commerce-common/umbraco-commerce-common-events/validationeventbase.md)

**Namespace**
* [Umbraco.Commerce.Core.Events.Validation](README.md)

### Constructors

#### ValidateDiscountAliasChange

```csharp
public ValidateDiscountAliasChange(DiscountReadOnly discount, ChangingValue<string> alias)
```


### Properties

#### Alias

```csharp
public ChangingValue<string> Alias { get; }
```


---

#### Discount

```csharp
public DiscountReadOnly Discount { get; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
