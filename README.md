# Temporal-Rich-Club
## Data
List of data sets analysed and presented in the "Temporal Rich Club Phenomenon" article by Pedreschi, Battaglia & Barrat.
All data sets are saved as .txt files in the "t, i, j" format.

- US Airline Data: airt transportation temporal network publicly available at https://www.transtats.bts.gov/, "Air Carrier Statistics (From 41 Traffic) - U.S. Carriers" data base, in the T-100 Domestic Segment section. The temporal network includes N=1920 airports in the US and monthly flight connections from January 2012 to September 2020. The directory includes the list of airport names and relative node indices.

- Primary School Temporal Network: 
publicly available at http://www.sociopatterns.org/datasets/primary-school-temporal-network-data/; temporal network of N=242 nodes, 232 students and 10 teachers. The original time resolution of the data set is 20s over two school days. We include here the temporal network obtained by a 5 minutes partial aggregation of the first school day presented in the main text. We also include the 5 minutes partial time aggregation over the two school days and the 1 minute partial time aggregation of the first school day, both presented in the Supplementary Information.


- Neuronal Assembly: the temporal network is made of N=67 nodes, representing spinking neurons in the hippocampus an entorhinal cortex in a rat. The temporal edges represent the amount of mutual information encoded in the firing patterns of each pair of neurons. The time resolution of the temporal network is 1s and the total duration is T=2284s.

## Notebooks
A guided python3 notebook to compute the cohesion of a temporal network for specific values of $k$ and $\Delta$, and to compute and plot the relative $k-\Delta$ diagram.
Required packages:
  - numpy
  - Pandas
  - matplotlib
  - NetworkX

The data set used in the hands-on example is the US Air Transportation network.
