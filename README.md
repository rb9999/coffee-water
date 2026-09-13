# Coffee Water Stock Calculator

A simple tool for mineralizing distilled/RO water for pour-over and drip coffee, using cheap food-grade chemicals instead of pre-made packets.

**Live pages:**
- Calculator: https://rb9999.github.io/coffee-water/
- Roast recipe guide: https://rb9999.github.io/coffee-water/recipes.html

## What this does

Coffee water quality (magnesium, calcium, and alkalinity levels) has a big effect on extraction and flavor. Instead of buying pre-made mineral packets, you can mix your own concentrated stock solutions from cheap ingredients and dose them precisely with this calculator.

## What you need

- **Distilled or RO water** — your base water, has no minerals of its own
- **Magnesium sulfate (Epsom salt)** — USP/food grade
- **Calcium chloride** — food grade, anhydrous or dihydrate form, check the label
- **An alkalinity source** — plain baking soda (sodium bicarbonate) or potassium bicarbonate, either works
- **A gram-accurate scale** (0.01g resolution ideal)
- 3 small bottles for storing your stock solutions (amber glass recommended, keeps light out)

## Step 1: Make your stock solutions

Do this once per chemical (3 total). Each stock is roughly a 10% solution (10g powder dissolved into a total of ~100g of solution), but the *exact* concentration is what matters, not hitting a round number:

1. Tare your scale, weigh the powder, record the exact figure (e.g. 10.02g)
2. Add distilled water to the same container (don't re-tare), record the exact new total (e.g. 101.87g)
3. Stir/shake until fully dissolved
4. Calculate concentration: `powder weight ÷ total weight × 1000 = mg/g`
   - Example: 10.02 ÷ 101.87 × 1000 = 98.4 mg/g
5. Label the bottle with the chemical, the mg/g value, and the date
6. Repeat for the other two chemicals in separate bottles

The calculator's **Stock concentration helper** (bottom of the page) will do this math for you — just enter your two weights and click "Apply" to drop the result straight into the right field. You can use this to make
whatever concentration of chemical you want as well. Doesn't have to be 10%.

## Step 2: Use the calculator

1. Enter your **water volume** (the starting amount of distilled water you'll be using — the stock gets added *to* this, you don't top off afterward)
2. Select your **calcium chloride form** (anhydrous or dihydrate — check your product label) and **alkalinity source** (baking soda or potassium bicarbonate)
3. Enter your **actual measured stock concentrations** (from Step 1) in the three fields — or use the **Roast level** slider to jump straight to a recommended starting recipe (Light / Medium / Dark / Extra dark), which also sets the Magnesium/Calcium/Alkalinity target sliders
4. The three result cards show exactly how many **grams** of each stock to add

## Step 3: Mix your brewing water

1. Weigh out your starting water amount
2. Add each stock solution by weight, directly on your scale, using the gram amounts from the calculator
3. Brew as usual

## Tasting and adjusting

- Too sour/thin → increase calcium
- Too bitter/flat → increase alkalinity
- Muted/dull → increase magnesium

Change one variable at a time between batches, using the same bean and brew recipe, so you can isolate what the water changed.

## Notes

- None of the three stock solutions need refrigeration — keep them capped, out of direct sunlight, and they're stable indefinitely
- Your entered volume/unit, stock concentrations, and roast slider position are saved automatically in your browser (localStorage) so they persist across visits — this is per-device/per-browser, not synced anywhere
