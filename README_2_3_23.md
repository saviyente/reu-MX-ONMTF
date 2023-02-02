Manipulated the EigGap at first to see the impact on the value of the delta. Significant results for delta from 0.95 to 0.2 (and d>=0.5 for finding_k). It resulted in k of 6. When seeing if the edges of the G graph are manipulated at a certain density threshold, there is little impact on k - change from 1 to 2. 
The data for EigGap delta of 0.2 and d>=0.5 for finding_k is "findK_eg2_d5_k6.mat".

Plotting "findK_eg2_d5_k6.mat": (provided "findK_eg21_d5_k6.mat" to show same output data different cut points, for repeatability) 

<img width="754" alt="z_figure" src="https://user-images.githubusercontent.com/76484772/216419307-596d4be6-b76a-4215-82f1-86004026b918.png">

-Attached is the Z dendrogram (Z_dgraph_eg2_k6) from code graph_Qd.m. I also attached the clusters graph. 
-I was struggling to understand how ClustersSupra worked concerning matrix and lots of graphing errors. 
  As a result, graphV2_Qd.m plots clusters of all layers given -"findK_eg2_d5_k6.mat", image file is. "clusters_graphV2_fixed_k6_kc3_kpl3". But DOES NOT highlight kc across layers. 
<img width="521" alt="clusters_eg02_d5" src="https://user-images.githubusercontent.com/76484772/216419354-3d13057b-aa90-449a-8194-56939b03bc4c.png">

-I also attached clusters for fixed data of k=6, kc=3, kp=3 for comparison – Figure clusters_graphV2_fixed_k6_kc3_kpl3. 
<img width="526" alt="clusters_fixed" src="https://user-images.githubusercontent.com/76484772/216419378-7cfa4d58-ea87-4d40-a271-193e42703e0e.png">
