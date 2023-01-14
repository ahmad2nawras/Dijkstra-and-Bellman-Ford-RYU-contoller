# Dijkstra-and-Bellman-Ford-RYU-contoller
The codes provided implements both Shortest-path algorithms Dijkstra and Bellmen Ford (BF) using RYU controller. <br/>
The codes use <b> networkx </b> library to virtualize the network and implement the algorithms as a running application on top of the SDN topology.
The codes has been tested on serveral topologies using <b>Mininet</b>.

## There is a possibility to use four different link costs:
- Bandwidth
- Delay
- Bandwidth + Delay
- Hops count

## To run the application using RYU:
- Run mininet with your topology:
```<Language>
sudo mn 'your topology'
```
- Install RYU in your Linux environement:
```<Language>
pip install ryu
```
- Run the application:
```<Language>
ryu-manager 'fileName.py (Dijktra or BF)'
```
