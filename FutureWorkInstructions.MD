# Future Work Instructions - Brooke Osterkamp - 4/27/23

## Step 1: Convert the COV data into usable data for processing

- File: `step1_data_Processing.mlx` contains function: `findingK_all.mlx`:

```
function [k, kc, kp] = findingK_all(Al, L)
```

- Output data file used: `COV_ks.mat`, contains `Kc`, `K`, `Kp`, `A`
- Note: No thresholding was used for data processing

## Step 2: Find the ClusterSupras

- File: `step2_cluster_Identify.mlx` contains function: `MX_ONMTF_real_OLD.mlx`:

```
function [H_bestNMI,Hl_bestNMI,ClustersSupra] = MX_ONMTF_real_OLD(A,k,kc,kpl)
```

- NOTE: Data runs for `MX_ONMTF_real` function was changed to 10 runs (instead of 20)
- Output data file used: `COV_ClustersSupra_run10.mat`, contains `ClustersSupra` labels

## Step 3: Using the data Plot the Graphs

- File: `step3_intercluster_COV.mlx`
- Output: all graphs interpreting data
- NOTE: `Component_brainRegion.xlsx` file contains the components number verse what the components are
- Output data file used: `COV_run10_Kc1.fig`, `COV_run10_Kc2.fig`, `COV_clusterId.fig`
![Screen Shot 2023-04-27 at 11 26 13 AM](https://user-images.githubusercontent.com/76484772/234910732-fbb8ed53-da7f-4c14-aafd-d3fec2d22016.png)
![Screen Shot 2023-04-27 at 11 26 18 AM](https://user-images.githubusercontent.com/76484772/234910748-34910baa-6bef-4298-8a20-11a126aee351.png)
![Screen Shot 2023-04-27 at 11 26 44 AM](https://user-images.githubusercontent.com/76484772/234910765-8a361a80-8a56-4219-aad7-b98e8a75a7bb.png)


## Interpretation

- The components with more private communities contain more variations between subjects.
- The community communities that contain component of normalized intercluster strength == 1, all subjects belong to community (little variation).
