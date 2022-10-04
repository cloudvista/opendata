## Markdown formatting tests


## Collapsible section
<details>
  <summary>Click to expand!</summary>
  
  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>



## Mermaid diagrams
https://mermaid-js.github.io/mermaid/#/sequenceDiagram


graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
    
 
 
 
 sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
    
    
 
