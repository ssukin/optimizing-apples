# Apple Orchard Allocation

A no-dependency, single-page model for comparing visitor picking with employee harvest.

Open `index.html` in a browser. Edit visitor reserve `v_t` and employee harvest `e_t` separately for each day in the results table. Choose weather for each day to adjust visitor demand (illustrative factors: sunny 1.2, cloudy 1.0, rainy 0.5). Prices, costs, ripe supply, and baseline demand are fixed illustrative inputs. The page compares your feasible daily decisions with the best feasible Solver plan.

The Solver setup is to maximize total daily profit by changing `v_t` and `e_t` for every day, subject to ripe supply, weather-adjusted visitor demand, store demand, labor, storage, and nonnegativity constraints. The numeric inputs are illustrative because the source slide defines the model but does not provide values or equations. The editable table cells correspond directly to the per-day Solver decision cells.
