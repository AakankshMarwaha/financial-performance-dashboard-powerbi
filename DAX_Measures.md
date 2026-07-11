# DAX Measures

This document contains the DAX measures used in the Financial Performance Dashboard.

---

## Total Revenue

```DAX
Total Revenue =
SUM(FactFinancial[Revenue])
```

---

## Total Profit

```DAX
Total Profit =
SUM(FactFinancial[Profit])
```

---

## Total Cost

```DAX
Total Cost =
SUM(FactFinancial[Cost])
```

---

## Total Budget

```DAX
Total Budget =
SUM(FactFinancial[Budget])
```

---

## Profit Margin %

```DAX
Profit Margin % =
DIVIDE([Total Profit], [Total Revenue], 0)
```

---

## Budget Variance

```DAX
Budget Variance =
[Total Revenue] - [Total Budget]
```

---

## Revenue per Transaction

```DAX
Revenue per Transaction =
DIVIDE([Total Revenue], [Total Transactions], 0)
```

---

## Profit per Transaction

```DAX
Profit per Transaction =
DIVIDE([Total Profit], [Total Transactions], 0)
```

---

## Average Discount %

```DAX
Average Discount % =
AVERAGE(FactFinancial[Discount])
```

---

## Total Quantity

```DAX
Total Quantity =
SUM(FactFinancial[Quantity])
```

---

## Total Transactions

```DAX
Total Transactions =
COUNTROWS(FactFinancial)
```
