# Apple Orchard Allocation

A no-dependency, single-page model for comparing visitor picking with employee harvest.

Open `index.html` in a browser. The two sliders are decision targets in pounds per day: visitor reserve `v` and employee harvest `e`. Fixed prices, costs, demand, and daily ripe-apple supply are scenario inputs, not sliders. The page shows the resulting allocation beside the daily Solver plan.

The Solver setup is to maximize total daily profit by changing `v_t` and `e_t`, subject to ripe supply, visitor demand, store demand, labor, storage, and nonnegativity constraints. The numeric inputs are illustrative because the source slide defines the model but does not provide values or equations. The demo repeats the slider targets across days; a full spreadsheet Solver model can use separate decision cells for each day.
