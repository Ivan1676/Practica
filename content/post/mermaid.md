+++
title = "Prueba de mermaid!!!"
date = 2021-01-10T00:00:00+08:00
description = "In-post APlayer testpage of Hugo theme Fuji"
tags = ["mermaid"]
aplayer = true
music = true
showLicense = false
weight = 4
+++


{{<mermaid align="left">}}
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{</mermaid>}}

<!--more-->


## Segunda prueba mermaid!!!!

{{<mermaid>}}
classDiagram
  Class01 <|-- AveryLongClass : Cool
  Class03 *-- Class04
  Class05 o-- Class06
  Class07 .. Class08
  Class09 --> C2 : Where am i?
  Class09 --* C3
  Class09 --|> Class07
  Class07 : equals()
  Class07 : Object[] elementData
  Class01 : size()
  Class01 : int chimp
  Class01 : int gorilla
  Class08 <--> C2: Cool label
{{</mermaid>}}

