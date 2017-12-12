# gcn-spp
Course project in IE532: Analysis of Network Data in 2017 Fall, UIUC.

## Our Team
| Name         | Guthub                                    |
|--------------|-------------------------------------------|
| Shizhao Wang | N/A                                       |
| Zhenye Na    | [Zhenye-Na](https://github.com/Zhenye-Na) |

## Primary work
Use Neural Network to estimate the length of shortest path of series of directed/undirected graphs. We have implemented this project with two different approaches - Deep Neural Network and Graph Convolutional Network.

## Dependencies
- Tensorflow (>= r1.3)
- Networkx (>= 1.10)
- matplotlib (>= 2.0.0)
- pandas (>=0.19.2)
- numpy (>=1.12.1)
- sklearn (>=0.0)

## Dataset we used
**Airlines Delay(Airline on-time statistics and delay causes) - Dataset**

The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics (BTS) tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled and diverted flights appears in DOT's monthly Air Travel Consumer Report, published about 30 days after the month's end, as well as in summary tables posted on this website. BTS began collecting details on the causes of flight delays in June 2003. Summary statistics and raw data are made available to the public at the time the Air Travel Consumer Report is released.

This version of the dataset was compiled from the Statistical Computing Statistical Graphics 2009 Data Expo and is also [available here](http://stat-computing.org/dataexpo/2009/the-data.html). We select data in 2008 as our input data.


**random_partition_graph in Networkx**

A partition graph is a graph of communities with sizes defined by s in sizes. Nodes in the same group are connected with probability p_in and nodes of different groups are connected with probability p_out.

## References
Graph convolutional network (Thomas N. Kipf, Max Welling, [Semi-Supervised Classification with Graph Convolutional Networks](http://arxiv.org/abs/1609.02907), 2016)
