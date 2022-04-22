---
marp: true
---

@startuml
start
:Add game to cart;
:Checkout;
:Check cookie;
while(if cookie?) is (is invalid)
:Show login form;
endwhile
fork
:Mail invoice;
fork again
:Load games;
end fork
:Install and play;
end
@enduml