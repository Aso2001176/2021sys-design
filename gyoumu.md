```uml
@startuml

ユーザー -> サイト : 検索(商品名,色)
サイト -> Tanazon : 検索処理(商品名,色)
Tanazon -> Tanazon : 検索処理
Tanazon -> サイト : 検索結果
サイト -> ユーザー : 検索結果

@enduml
```
