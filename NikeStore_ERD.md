erDiagram
    CUSTOMER }|..|{ DELIVERY-Information : has
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER ||--o{ INVOICE : "liable for"
    DELIVERY-Information ||--o{ ORDER : receives
    INVOICE ||--|{ ORDER : covers
    ORDER ||--|{ ORDER-ITEM : includes
    PRODUCT-Inventory ||--|{ nikeshoes : contains
    nikeshoes||--o{ ORDER-ITEM : "ordered in"
    Inventory||--|{ PRODUCT-Inventory : "check Inventory"
    sales ||--|{Inventory: "track sales"

  designed a system that tracks customers orders,information and checks inventory and sales. 
