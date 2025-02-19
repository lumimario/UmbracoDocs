---
title: OrderLineCalculationPipelineArgs
description: API reference for OrderLineCalculationPipelineArgs in Umbraco Commerce
---
## OrderLineCalculationPipelineArgs

```csharp
public class OrderLineCalculationPipelineArgs : PipelineArgs<OrderLineCalculation>
```

**Inheritance**

* class [PipelineArgs&lt;!0&gt;](../../umbraco-commerce-common/umbraco-commerce-common-pipelines/pipelineargs-1.md)

**Namespace**
* [Umbraco.Commerce.Core.Pipelines.OrderLine](README.md)

### Constructors

#### OrderLineCalculationPipelineArgs

```csharp
public OrderLineCalculationPipelineArgs(IUnitOfWork uow, OrderLineCalculation model, 
    StoreReadOnly store, OrderReadOnly order, OrderLineReadOnly orderLine, 
    CurrencyReadOnly currency, TaxSource taxSource, TaxRate fallbackTaxRate)
```


### Properties

#### Calculation

```csharp
public OrderLineCalculation Calculation { get; }
```


---

#### Currency

```csharp
public CurrencyReadOnly Currency { get; set; }
```


---

#### FallbackTaxRate

```csharp
public TaxRate FallbackTaxRate { get; set; }
```


---

#### Order

```csharp
public OrderReadOnly Order { get; set; }
```


---

#### OrderLine

```csharp
public OrderLineReadOnly OrderLine { get; set; }
```


---

#### Store

```csharp
public StoreReadOnly Store { get; set; }
```


---

#### TaxSource

```csharp
public TaxSource TaxSource { get; set; }
```


<!-- DO NOT EDIT: generated by xmldocmd for Umbraco.Commerce.Core.dll -->
