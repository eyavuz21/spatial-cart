# 🛒 SpatialCart

**Plans the cheapest practical shopping route across the real supermarkets around you, then tracks every pound you save.**

**🔴 Live demo: <https://eyavuz21.github.io/spatial-cart/>**

![SpatialCart landing page](docs/screenshot.png)

Built at the **Pop The Bubble Hackathon**. Give it your shopping list and it treats grocery shopping as a routing problem: it sends you to the cheapest nearby stores that actually have everything on your list, using real supermarket locations from OpenStreetMap. (Prices are simulated and crowdsourced for the demo.)

The idea came straight out of my PhD work on how people navigate real-world environments. Its sibling project, [ParkAndSave](https://github.com/eyavuz21/park-and-save), extends the same "optimise the errand" idea with an LLM agent and generative UI.

## Files

- `index.html`: landing page
- `app.html`: the route planner
- `journey.html`: the saved-journey / savings tracker
