# Fjelltopp Pizza Oven Module Tests

```
import mdtest
import dough from ./super-legit-pizza-dough.md;
import Oven from kitchen-equipment;

@mdtest.mark.parametrize('baking_surface, baking_temperature', [
    (grill, 250C),
    (stone, 250C),
    (steel, 250C),
    (stone, 485C),
])
def test_pizza_oven_is_pizza_cooked(baking_surface, baking_temperature):
    pizza_oven = Oven(baking_surface, baking_temperature);
    pizza = pizza_oven.bake(dough);
    assert pizza.is_cooked()
    
def test_pizza_oven_is_pizza_cooked_perfectly():
    pizza_oven = Oven(stone, 485C);
    pizza = pizza_oven.bake(dough);
    assert pizza.is_cooked_perfectly()
```
