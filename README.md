# Time-Curve Betting Simulation 🍏

A Python-based parimutuel betting simulation with a novel "Time-Curve" mechanism, featuring a minimalist Apple-style UI.

![Dashboard Screenshot](https://raw.githubusercontent.com/placeholder/screenshot.png)

## Features

-   **Time-Curve Mechanism**: Late bettors are penalized (Favorites) or rewarded (Underdogs) based on a power decay function.
-   **Agent Simulation**: Simulates 100 agents (Believers, Snipers, Degens) to stress-test the market.
-   **Apple Style UI**: Clean, glassmorphic design with San Francisco typography and pastel charts.
-   **Interactive Visualizations**: Real-time updates of multiplier curves, ROI heatmaps, and betting volume.

## Running Locally

1.  Install dependencies:
    ```bash
    pip install streamlit pandas plotly numpy
    ```
2.  Run the app:
    ```bash
    streamlit run app.py
    ```

## Decentralized Deployment (IPFS)

This app can be compiled to a static HTML file using `st-lite` (Pyodide) for hosting on IPFS.
See `ipfs_build/index.html` (generated via build steps).

## License

MIT
