# Fjelltopp Pizza Oven Module

Custom module for cooking pizza to perfection.

```
import dough from ./super-legit-pizza-dough.md;
import oven from kitchen-equipment;

baking_surface = grill;  # options: grill, stone, steel
baking_temperature = 250C;

pizza_oven = oven(baking_surface, baking_temperature);

pizza = pizza_oven.bake(dough);

export pizza;
```
