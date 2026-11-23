# HyBills Stores & Food → Storefront Hero Asset Package

Engineered specifically for independent layer animation in React with CSS/Motion.
Matches the approved HyBills Storefront dark Apple-grade aesthetic.

## Directory Structure

```
public/assets/
├── BURGER/
│   ├── hybills-burger-complete.png      (1024x1024 reference intact master)
│   ├── hybills-burger-top-bun.png       (Brioche sesame crown)
│   ├── hybills-burger-lettuce.png       (Crisp ruffled green lettuce)
│   ├── hybills-burger-tomato.png        (Ripe sliced tomatoes)
│   ├── hybills-burger-cheese.png        (Melted cheddar drape & drips)
│   ├── hybills-burger-patty.png         (Flame-grilled prime beef patty)
│   ├── hybills-burger-sauce.png         (Chili-mayo relish glaze)
│   ├── hybills-burger-bottom-bun.png    (Toasted brioche base)
│   ├── hybills-burger-crumbs.png        (Floating sesame seeds & seasoning)
│   ├── hybills-burger-fries.png         (Seasoned fries carton side)
│   └── hybills-burger-drink.png         (Cold iced soda with straw)
├── PIZZA/
│   ├── hybills-pizza-whole.png          (Artisan wood-fired whole pizza)
│   ├── hybills-pizza-slice-01.png       (Pulled slice with melted cheese string)
│   ├── hybills-pizza-slice-02.png       (Sector slice for fan animation)
│   ├── hybills-pizza-basil.png          (Fresh green basil leaves)
│   └── hybills-pizza-particles.png      (Oregano & red pepper chili flakes)
├── JOLLOF/
│   ├── hybills-jollof-bowl.png          (Matte dark ceramic bowl foundation)
│   ├── hybills-jollof-rice.png          (Authentic smoky Nigerian party jollof)
│   ├── hybills-jollof-plantain.png      (Fried sweet plantain slices / dodo)
│   ├── hybills-jollof-chicken.png       (Juicy roasted chicken with pepper glaze)
│   ├── hybills-jollof-garnish.png       (Scotch bonnet pepper strips & scallions)
│   └── hybills-jollof-steam.png         (Drifting atmospheric steam overlay)
└── manifest.json                        (Machine-readable animation manifest)
```

## Critical Stacking Alignment

All 7 burger layers share the identical `1024x1024` coordinate space.
When stacked at `translateY: 0`, they reconstruct the single master burger with zero clipping or misalignment.
When exploded, animate their `translateY` values according to the vector specifications in `manifest.json`.
