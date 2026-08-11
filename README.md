# AI-LAB5-UCS
Lab 3 — Uniform Cost Search
## My Approach
I approached this by first working out all three possible routes from A to D by hand and comparing their total costs, which showed that the cheapest route (A-B-C-D, cost 4) actually has the most hops — not the fewest. I then modified the BFS structure to store (cost, path) pairs instead of plain paths, sort the queue by cost before every pop, and check for the goal only after popping, so the search always expands the cheapest known option first and never accepts a costlier path before a cheaper one has a chance to surface.

Files: AI-LAB3.py, notes, and output screenshot.
<img width="1060" height="128" alt="image" src="https://github.com/user-attachments/assets/3102ce36-a076-441d-afda-462e434792fe" />
