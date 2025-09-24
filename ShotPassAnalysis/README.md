# Shot and Pass Plotting in Football

This project visualizes football (soccer) shot locations and passing patterns using Python and Matplotlib.  
It provides intuitive plots that highlight player movement, passing networks, and shot distributions during a match.

## Features
- Plot shot locations (goals, misses, saves)
- Visualize passing maps between players
- Annotate players and key passes on pitch diagrams
- Modular functions for reuse on new match data

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib

## Example Visualization
- Shot maps with xG zones
- Pass networks with player nodes and link thickness based on pass frequency

## How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/paritosh100/Shot-and-Pass-plotting-using-python.git
   cd Shot-and-Pass-plotting-using-python
   ```
2. Install dependencies  
   ```bash
   pip install pandas numpy matplotlib
   ```
3. Open the notebook  
   ```bash
   jupyter notebook "Untitled (1).ipynb"
   ```

## Output
Generates plots showing:
- Heatmaps of shot locations
- Player passing links and field control

## Next Steps
- Add player-level stats integration
- Incorporate expected goals (xG) modeling
