---
title: OrderPropertiesAdvancedFilter
description: API reference for OrderPropertiesAdvancedFilter in Umbraco Commerce
---
## OrderPropertiesAdvancedFilter

```csharp
public class OrderPropertiesAdvancedFilter : OrderAdvancedFilterBase
```

**Inheritance**

* class [OrderAdvancedFilterBase](../umbraco-commerce-cms-filters/orderadvancedfilterbase.md)

**Namespace**
* [Umbraco.Commerce.Cms.Filters.Implement](README.md)

### Constructors

#### OrderPropertiesAdvancedFilter

The default constructor.

```csharp
public OrderPropertiesAdvancedFilter()
```


### Methods

#### Apply

```csharp
public override IQuerySpecification<OrderReadOnly> Apply(IQuerySpecification<OrderReadOnly> query, 
    IOrderQuerySpecificationFactory where, string value)
```


---

#### CanApply

```csharp
public override bool CanApply(string value)
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Cms.dll -->
