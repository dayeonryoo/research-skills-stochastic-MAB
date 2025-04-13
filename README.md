To recreate the plots in the essay, please do the followings:

- Run stationary_algorithms.ipynb to recreate

    FIG 1. Fixed Exploration with N as a fraction of T

    FIG 3. Epsilon-Greedy with constant epsilon

    FIG 4. Epsilon-Greedy with decaying epsilon

    FIG 5. UCB with constant c

    FIG 6. Sensitivity analsysis of the 4 algorithms with respect to optimality gap

    FIG 11. Cumulative Regret under uniform and non-uniform rewards. Compares both algorithms across environments.

- Run fe_optimal_N.ipynb to recreate

    FIG 2. Fixed Exploration with optimal N as a function of log(T)
    
  (Note that fe_optimal_N.ipynb calls fixed_exploration.py)

- To get the figures for the Non stationary MAB. Run the code "NS_UCB_MAB.ipynb”

    FIG 7. Abruptly-changing Environment (Env_1_rewards.png, Env_1_regret.png)

    FIG 8. Gradually-changing Environment (Env_2_rewards.png, Env_2_regret.png)

    FIG 9. Evolution of Cumulative Regret as a function of time, with tuned hyperparameters, in abruptly-changing environment (Discounted_regret_different_gamma.png, SlidingWindow_regret_different_tau.png)

    FIG 10. Evolution of Cumulative Regret as a function of time, with different no. of arms in abruptly-changing environment (Regret_newPrices_Discounted.png, Regret_newPrices_SW.png)
