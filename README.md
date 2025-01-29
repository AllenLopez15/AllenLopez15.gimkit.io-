# https-AllenLopez15.github.io
```mermaid
erDiagram
PRODUCT ||--o{ Customer : Interest
PRODUCT{
Shoes Footwear
shirts bodywear
hoodies bodywear
}
CUSTOMER ||--|{ Sale : Price
CUSTOMER{
Consumers thepeople
Sponsors BigEvents
Famous Attention
}
SALE ||--|{ Inventory : Product
SALE{
prices affordable
}
INVENTORY{
Supplies MoreProducts
}
```
