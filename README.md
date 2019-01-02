# Pivot-Clustering
Implementation of the Pivot Algorithm used for Cluster Aggregation

The following publications provide detailed  information about the algorithm:
- A. Gionis, H. Mannila, P. Tsaparas, Clustering aggregation, ACM Transactions on Knowledge Discovery from Data 1(1), 2007.
- N. Ailon, M. Charikar, A. Newman, Aggregating inconsistent information: ranking and clustering, Journal of the ACM 55(5), 2008
- G. Gursun, N. Ruchansky, E. Terzi, M. Crovella, Routing state distance: a path-based metric for network analysis, IMC, 2012.

To use Pivot, make sure that the directory containing the pivot package is in your classpath, then give
```
  java pivot.Pivot c1.rsf c2.rsf ... c3.rsf out.rsf
```
to aggregate n different clustering of the same set of items and store the aggregated clustering in out.rsf
