# Reto-6
Reto 6
Primer diagrama 
  flowchart TD
    A["Inicio"] --> B["i = 0"]
    B --> C{"while i <= 100"}
    C -- Sí --> D["Imprimir i y i^2"]
    D --> E["i = i + 1"]
    E --> C
    C -- No --> F["Fin"]

