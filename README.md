# Apple Orchard Allocation

A no-dependency, single-page model for comparing visitor picking with employee harvest.

Open `index.html` in a browser. Visitor reserve `v` and employee harvest `e` are the daily decision targets. Their sliders repeat the same target each day. Choose weather for each day in the results table to adjust visitor demand (illustrative factors: sunny 1.2, cloudy 1.0, rainy 0.5). Prices, costs, ripe supply, and baseline demand are fixed illustrative inputs. The page compares the selected daily targets with the best feasible Solver plan.

The Solver setup is to maximize total daily profit by changing `v_t` and `e_t`, subject to ripe supply, visitor demand, store demand, labor, storage, and nonnegativity constraints. The numeric inputs are illustrative because the source slide defines the model but does not provide values or equations. The demo repeats the decision targets across days; a full spreadsheet Solver model can use separate decision cells for each day.
