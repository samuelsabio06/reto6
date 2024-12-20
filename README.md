# Reto 6
---
- Punto 1
```mermaid
---
config:
  layout: elk
  look: handDrawn
  theme: dark
---
flowchart TB
  A([Inicio]) --> B[n=1] --> C{n <= 100?} -->|si|D
  D[hacer i ^2] --> E[Aumentar i una unidad]-->C
  C-->|no|F([fin del programa])
 ```
---
- Punto 2

```mermaid
---
config:
  layout: elk
  look: handDrawn
  theme: dark
---
flowchart TB
  A([Inicio]) --> B[n=0] --> C{Es  n <= 1000?}
  C-->|Si|D{Es divisible exactamente entre 2?}
  D-->|si|E[n es par]
  D-->|no|F[n es impar]
  F --> G[Imprimir el numero n en la lista correspondiente]
  E-->G
  G--> H[n += 1]
  H-->C
  C-->|No|I[Mostrar los resultados de cada lista]
  I-->J([Fin])


  

  
  ```
---
- Punto 3
```mermaid
---
config:
  layout: elk
  look: handDrawn
  theme: dark
---
flowchart TB
  A([Inicio]) --> B[n = 2]
  B--> C[Entra en valor de i]-->F
  
  F{Es i >= n?}
  F-->|no|Z([Fin])
  F-->|si|J{Es par?}
  J-->|si|H[Imprimir el numero]-->K[i -= 1]
  J-->|No|i[Omitir el numero]-->K-->F
  




  

  
  ```
  

  
  
