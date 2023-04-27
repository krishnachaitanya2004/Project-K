READ ME

Step 1:
Download Champsim software from the below link
https://github.com/ChampSim/ChampSim

Step 2:
Place the project_k.l1d_pref and project_k.l2c_pref files in champsim/Champsim/prefetcher

Step 3:
Open terminal in champsim/Champsim folder

Step 4:
Run the following command
./build_champsim.sh bimodal no ipcp ipcp next_line lru 1

Step 5:
Place the traces in champsim/traces folder

Step 6:
./run_champsim.sh bimodal-no-project_k-project_k-next_line-lru-1core 30 30 {trace}

use the exact name of trace
