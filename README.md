# A-Topological-Framework-for-Identifying-Structural-Breaks-in-Cross-Asset-Cryptocurrency-Network
![Figure 1](https://raw.githubusercontent.com/Janeyaoo/A-Topological-Framework-for-Identifying-Structural-Breaks-in-Cross-Asset-Cryptocurrency-N/main/Fig1.png)

Overview

The cryptocurrency market exhibits pronounced volatility and structural fragility. Traditional risk indicators—such as price volatility, market indices, and sentiment measures—mainly capture price-level fluctuations and often fail to reveal deeper structural breaks.

This study introduces a topological data analysis (TDA) framework for detecting structural state transitions by tracking the evolving topology of cross-asset similarity networks and identifying latent sources of systemic instability.

Methodology
	•	Compute Wasserstein distance and Dynamic Time Warping (DTW) within a sliding-window scheme.
	•	Construct Vietoris–Rips complexes on similarity networks.
	•	Extract key topological features: Betti-0, Betti-1, and persistent entropy.
	•	Align topological indicators with realized market events (2020-2025) using data from the ten largest cryptocurrencies by market capitalization.
	•	Benchmark performance using ROC–AUC and three structural break detection methods: PELT, Binary Segmentation, and CUSUM.

Key Findings
	•	TDA-based indicators consistently outperform traditional market measures.
Topological connectivity features (Betti-0) achieve AUC scores of 0.632–0.650, exceeding the performance of the
Fear & Greed Index, BTC volatility, S&P 500, and VIX.
	•	Across all three structural break detection procedures, TDA indicators achieve the highest F1-scores, surpassing both standard market indicators and BTC volatility in identifying structural transitions.

Conclusion

Topology-based measures provide a powerful and complementary perspective for detecting structural breaks in cryptocurrency markets.
They capture system-level connectivity changes that conventional price-based indicators often miss, offering meaningful applications in portfolio risk management, crisis monitoring, and systemic stability assessment.

