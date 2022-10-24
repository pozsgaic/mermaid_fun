# mermaid_fun
Some sample mermaid and other github markdown

```mermaid
C4Deployment
    title Deployment Diagram for Trading System - Live

    Deployment_Node(mob, "Mobile device", "IPhone/Android"){
        Container(mobile, "Mobile App", "HTTP2", "Subset of functions")
    }

    Deployment_Node(pc, "PC", "Windows"){
        Container(pc, "PC", "HTTP2/RPC", "Full client suite of functions")
    }

    Deployment_Node(api, "API", "REST"){
        Container(api, "api", "HTTP2/RPC", "Full suite of functions")
    }
    
```

```mermaid
sequenceDiagram
    participant C as Consumer
    participant P as Producer
    C->>P: Is data available?
    P-->>C: Please check the queue
```

```mermaid
graph TD;
    1-->2;
    1-->3;
    2-->4;
    2-->5;
    3-->6;
    3-->7;
    7-->8;
    7-->9;
```
```stl
solid cube
  facet normal 1.0 0.0 0.0
    outer loop
      vertex 1.0 0.0 0.0
      vertex 1.0 1.0 0.0
      vertex 1.0 0.0 1.0
    endloop
  endfacet
  facet normal 1.0 0.0 0.0
    outer loop
      vertex 1.0 1.0 0.0
      vertex 1.0 1.0 1.0
      vertex 1.0 0.0 1.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.0 1.0 0.0
    outer loop
      vertex 0.0 1.0 0.0
      vertex 0.0 1.0 1.0
      vertex 1.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.0 1.0 0.0
    outer loop
      vertex 1.0 1.0 0.0
      vertex 0.0 1.0 1.0
      vertex 1.0 1.0 1.0
    endloop
  endfacet
  
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 1.0 0.0 0.0
      vertex 1.0 0.0 1.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  
  facet normal 0.0 0.0 1.0
    outer loop
      vertex 0.0 0.0 1.0
      vertex 1.0 0.0 1.0
      vertex 0.0 1.0 1.0
    endloop
  endfacet
  
  facet normal 0.0 0.0 1.0
    outer loop
      vertex 1.0 0.0 1.0
      vertex 1.0 1.0 1.0
      vertex 0.0 1.0 1.0
    endloop
  endfacet
  
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 1.0 0.0
      vertex 1.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  
  endsolid
  
  solid single_face
    facet normal 1.0 0.0 0.0
      outer loop
        vertex 5.0 0.0 0.0
        vertex 5.0 1.0 0.0
        vertex 5.0 0.0 1.0
      endloop
    endfacet
    facet normal 1.0 0.0 0.0
      outer loop
        vertex 5.0 1.0 0.0
        vertex 5.0 1.0 1.0
        vertex 5.0 0.0 1.0
      endloop
    endfacet
  endsolid 
```
