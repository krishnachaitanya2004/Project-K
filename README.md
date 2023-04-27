# How to run the code

1. Download the ChampSim software from [GitHub](https://github.com/ChampSim/ChampSim).
2. Place the `project_k.l1d_pref` and `project_k.l2c_pref` files in `champsim/Champsim/prefetcher`.
3. Open the terminal in the `champsim/Champsim` folder.
4. Run the following command: `./build_champsim.sh bimodal no project_k project_k next_line lru 1`.
5. Place the traces in `champsim/traces` folder.
6. Run the following command to execute the simulation: `./run_champsim.sh bimodal-no-project_k-project_k-next_line-lru-1core 30 30 {trace}`, using the exact name of the trace.

> Note: Make sure to replace `{trace}` with the name of the trace file you want to use.
