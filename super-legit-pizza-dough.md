# Alex "French Guy Cooking"'s Super Legit Pizza Dough Recipe

Upstream: http://www.frenchguycooking.com/recipe/my-super-legit-pizza-dough

## Metadata

Prep: 60 minutes
Cook: 5 minutes
Servings: 1

## Imports

import 173.33g from flour;
import 121.67g from water;
import 5.33g from salt;
import 0.5g from yeast;
import bowl from kitchen-equipment;

## Instructions

1. dough = bowl + water;
2. dough.append(salt);
3. dough.append(50g * flour);
4. dough.append(yeast);
5. while (flour.remaining() > 0) {dough.append(some(flour))};
6. while (!dough.issmooth()) {knead(dough)};
7. pause(7200);
8. shape(dough);
9. pause(21600);

export dough;
