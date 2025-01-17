---
title: Region
description: API reference for Region in Umbraco Commerce
---
## Region

```csharp
public class Region : RegionReadOnly
```

**Inheritance**

* class [RegionReadOnly](regionreadonly.md)

**Namespace**
* [Umbraco.Commerce.Core.Models](README.md)

### Methods

#### Create (1 of 2)

```csharp
public static Region Create(IUnitOfWork uow, Guid storeId, Guid countryId, string code, string name)
```

---

#### Create (2 of 2)

```csharp
public static Region Create(IUnitOfWork uow, Guid id, Guid storeId, Guid countryId, string code, 
    string name)
```


---

#### ClearDefaultPaymentMethod

```csharp
public Region ClearDefaultPaymentMethod()
```


---

#### ClearDefaultShippingMethod

```csharp
public Region ClearDefaultShippingMethod()
```


---

#### SetCode

```csharp
public Region SetCode(string code)
```


---

#### SetDefaultPaymentMethod

```csharp
public Region SetDefaultPaymentMethod(Guid? paymentMethodId)
```


---

#### SetDefaultShippingMethod

```csharp
public Region SetDefaultShippingMethod(Guid? shippingMethodId)
```


---

#### SetName

```csharp
public Region SetName(string name)
```


---

#### SetSortOrder

```csharp
public Region SetSortOrder(int sortOrder)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
