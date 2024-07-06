# Reachability, Burstiness and Motifs in Graphs:
There is a datafile attached to this exercise which can also be found at its source:

https://snap.stanford.edu/data/email-Eu-core-temporal.html

This is a temporal data, the file has three columns separated by space, the first is the id of the sender, the second is the id of the receiver, the third is a timestamp. 

## 1. Reachability

Recreate the reachability curves on pages 41-46. Start from a random node. Pass an information if there is an event from an information holder to another agent. Repeat the experiment few dozen times with different sources and plot the average

• repeat the above with time shuffling. Here randomly shuffle the third column

• repeat the above with link shuffling. Take two links: A->B, C->D, shuffle it to A->D, C->B. In other words shuffle the second column

• repeat the above experiment with both shufflings

![image](https://github.com/eva-vision/Reachability-Burstiness-Motifs-in-Graphs/assets/52841811/56cd6822-a811-4221-aff4-46211bcf8bcb)
Figure 1: Reachability

## 2. Time Distribution and Burstiness

Measure the interevent time distribution and the burstiness. Here interevent time is defined as the time interval between two actions by the same agent


![image](https://github.com/eva-vision/Reachability-Burstiness-Motifs-in-Graphs/assets/52841811/28de79d4-655a-4306-95e5-b4c323874f25)
Figure 2: Intervent Time Distribution

![image](https://github.com/eva-vision/Reachability-Burstiness-Motifs-in-Graphs/assets/52841811/ea189487-63d1-4f4c-95f4-c7cf87ed2063)
Figure 3: Burstiness


## 3. Statistics of Six Pre-defined Causal and Non-causal Motifs

Choose 6 different motifs both causal and non-causal ones in the original and the time shuffled version. Compare the relative frequencies for at least 3 different time window.

![image](https://github.com/eva-vision/Reachability-Burstiness-Motifs-in-Graphs/assets/52841811/1bed7266-ed1a-438c-9b6c-b860dc72e068)
Figure 4: Pre-defined Motifs

![image](https://github.com/eva-vision/Reachability-Burstiness-Motifs-in-Graphs/assets/52841811/fd0beeb0-a030-4175-8a7f-2f10a5a8a650)
Figure 5: Motif Frequency Comparision in Different Time Windows
