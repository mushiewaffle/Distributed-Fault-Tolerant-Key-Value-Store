<p align="center">
  <img src="images/DKV-title.png" />
</p>
<p align="center">
  Built a REST-accessible, sharded, replicated Key-Value store on a collection of Docker instances. Causal consistency maintained with vector clocks ensuring events take place in the right order.</br>
  Implemented Fault-Tolerance with consistent hashing, so if one node fails, it fails independently. A node failing results in its information being redistributed to a successor node without affecting other nodes, increasing performance by over 300%.</br>
  Supports view operations, shared operations, and key-value operations.
</p>
<h1></h1>
<h3 align="center">Causal Consistency</h3>
<p align="center">
  <img src="images/DS-causalanomaly.png" />
  <img src="images/DS-causalbroad.png" />
</p>
<h3 align="center">Consistent Hashing</h3>
<p align="center">
  <img src="images/DS-default.png" />
  <img src="images/DS-newnode.png" />
  <img src="images/DS-crash.png" />
</p>
