```plantuml
@startuml
'https://plantuml.com/sequence-diagram

autonumber

Alice -> Bob: Authentication Request
Bob --> Alice: Authentication Response

note right: [[flow_b.puml flow b]]

Alice -> Bob: Another authentication Request
Alice <-- Bob: another authentication Response
@enduml