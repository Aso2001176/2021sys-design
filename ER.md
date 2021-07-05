```startuml
@startuml
注文 }|..|| 商品
商品 }o..o| 在庫
顧客 ||--o{ 商品
注文 |o--|| 顧客
@enduml
```
