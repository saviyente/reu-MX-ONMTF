Manipulated the EigGap at first to see the impact on the value of the delta. Significant results for delta from 0.95 to 0.2 (and d>=0.5 for finding_k). It resulted in k of 6. When seeing if the edges of the G graph are manipulated at a certain density threshold, there is little impact on k - change from 1 to 2. 
The data for EigGap delta of 0.2 and d>=0.5 for finding_k is "findK_eg2_d5_k6.mat".

Plotting "findK_eg2_d5_k6.mat":
![My Image](z_figure.jpg)
-Attached is the Z dendrogram (Z_dgraph_eg2_k6) from code graph_Qd.m. I also attached the clusters graph. 
-I was struggling to understand how ClustersSupra worked concerning matrix and lots of graphing errors. 
  As a result, graphV2_Qd.m plots clusters of all layers given -"findK_eg2_d5_k6.mat", image file is. "clusters_graphV2_fixed_k6_kc3_kpl3". But DOES NOT highlight kc across layers. 
 ![My Image](clusters_eg02_d5.jpg)
-I also attached clusters for fixed data of k=6, kc=3, kp=3 for comparison – Figure clusters_graphV2_fixed_k6_kc3_kpl3. 
![My Image](clusters_fixed.jpg)
