# Alex "French Guy Cooking"'s Super Legit Pizza Dough Recipe

Upstream: http://www.frenchguycooking.com/recipe/my-super-legit-pizza-dough

```
import 173.33g from flour;
import 121.67g from water;
import 5.33g from salt;
import 0.5g from yeast;
import bowl from kitchen-equipment;

dough = bowl + water;
dough.append(salt);
dough.append(50g * flour);
dough.append(yeast);
while (flour.remaining() > 0) {dough.append(some(flour))};
while (!dough.issmooth()) {knead(dough)};
pause(7200);
shape(dough);
pause(21600);


export dough;
```
