Model comparison folder
=======================

Priority benchmark outputs copied/generated here.

Primary rank 2-10 benchmark:
- PCA_CP_VAE_CPVAE_rank2_to_rank10_reconstruction_ROC_curves.pdf
- PCA_CP_VAE_CPVAE_rank2_to_rank10_standardized_model_metrics.csv
- PCA_CP_VAE_CPVAE_rank2_to_rank10_benchmark_summary.pdf

Primary rank 6 benchmark:
- PCA_CP_VAE_CPVAE_rank6_reconstruction_ROC_curves.pdf
- PCA_CP_VAE_CPVAE_rank6_standardized_model_metrics.pdf/csv
- rank6_primary_metrics.csv

Program-level comparison:
- PCA_CP_VAE_CPVAE_rank6_program_landscapes.pdf
- PCA_CP_VAE_CPVAE_rank6_program_distinctness_correlation_heatmaps.pdf

Legacy core metrics retained:
- Model_performance_reconstruction_MSE.pdf
- Model_performance_reconstruction_R2.pdf
- Model_performance_reconstruction_metrics.csv

Rank 6 current metrics:
Model  Rank      MSE     RMSE      MAE  NRMSE_by_observed_sd  Pearson_r_observed_vs_reconstructed  Explained_variance  Strong_signal_ROC_AUC
  PCA     6 0.448850 0.669963 0.468282              0.669963                             0.742395            0.551150               0.788232
   CP     6 0.478917 0.692038 0.481536              0.692038                             0.721895            0.521133               0.773234
  VAE     6 0.386508 0.621698 0.432406              0.621698                             0.784139            0.613502               0.832359
CPVAE     6 0.409421 0.639860 0.454492              0.639860                             0.772145            0.591374               0.841599
