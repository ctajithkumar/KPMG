# DemoChallenge
<h1 class="code-line" data-line-start=0 data-line-end=1 ><a id="KPMGChallenge"></a>KPMGChallenge</h1>
<p class="has-line-data" data-line-start="2" data-line-end="9">1 - 3-Tier Architecure creation<br>
- Architecture diagram : <a href="https://github.com/ctajithkumar/KPMG/blob/master/3-tier%20implementation/Architecture%20Diagram.png">https://github.com/ctajithkumar/KPMG/blob/master/3-tier implementation/Architecture Diagram.png</a><br>
- Subnets have been used to steamline network communication<br>
- Only one public IP used for the fron end Load Balancer, all other and Load Balancers and NICs are only usng private IP asigned by the subnet<br>
- Azure SQL with DR in a differnt region created with a failover group mechanism to enable automatic failover in case the primay region goes down<br>
- Load balancing rules are used to route to specific ports from incoming to backend<br>
- Azure Availability Sets have been used to get more SLA in terms of the uptime of 99.95%</p>
<p class="has-line-data" data-line-start="10" data-line-end="15">
