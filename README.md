<h1>
Peer Request Protocol is a HTTP request incentivization system 🤝
</h1>

<p>Imagine that Alice, is a video content creator. She uploads videos to YouTube but she barely gets any views on them. She decides that she would rather have 1000 views per video she uploads rather than her usual 27 views.</p>

<p>Alice now has a choice, she can go the conventional route of paying the platform YouTube directly for advertising, and have the content be served to users, or, she can try out a new experimental technology, this is where PRP comes in!</p>

<p>Peer Request Protocol is a smart contract that allows for Requesters such as Alice, to outline an SLA to be filled. It is then the responsibility of Peers, which we will call Bob, to fulfil this contractual agreement and make it a reality.</p>

<p>
<ul>
  <li>You want 10.000 views on a video? Peers can do that.</li>
  <li>You want to post 30 forum posts at once on a website? Peers can do that.</li>
  <li>You want content to reach a certain number of likes and shares inside of an SLA? You get the picture.</li>
</ul>
</p>

<h1>Pilot 🛫</h1>

<p>For a proof-of-concept goal of this technology, the goal will be having a tweet reach 10 likes via direct usage of the protocol</p>

<h2>How the POC will be demonstrated </h2>
It will fulfill this action with the simple x step process:

<div>
<ol>
  <li>Interface, where a user submits a link to a tweet they want liked
</li>
  <li>Being able to pay a transaction for the smart contract to fulfil this request
</li>
  <li>Sufficient peer power and a network who's incentives matches the want to accept this job
</li>
</ol>
</div>

<p>
  There are 3 layers to the blockend, they consist of:
  <ol>
  <li>The Oracle Layer</li>
  <li>The Peer Network</li>
  <li>The Smart Contract</li>
  </ol>
</p>

<p>Frameworks for Oracles exist, such as Chainlink, and of course, so do ones for SmartContracts, but Peer Request Protocol will have to erect it's own Peer network, here is how it will be done:</p>

<ol>
  <li>Create an erc20 token, that may become a governance token in the future named $PRP</li>
  <li>Find Peers that would be willing to participate in this experiment, and give them some $PRP completely free</li>
  <li>Have a very intuitive peer dashboard UI, in which the peer will be guided to preform given tasks</li>
  <li>Have such an incentives mechanism in place so that once the network is Bootstrapped, peers will commit to responding to requests</li>
</ol>

<p>Initially, for reasons of the POC, there will be heavy bootstrapping of the peer network, however, the real value would emerge if the $PRP peer network is able to incentivize itself all through the requestor to peer cycle, without the need for constant monitoring from part of the team.</p>

<img alt="image of the incentivisation mechanism" src="./diagrams/MVP_Incentives_mechanism.png"></img>

<h1>Success criteria ✅</h1>

<p>The POC will be marked as a success if the following things happen: </p>
<ol>
  <li>Oracles can verify if a post was made inside of an SLA</li>
  <li>The contract can recieve the response from the oracles that the post was made</li>
  <li>The interface exists on the contract level and can be called by anyone</li>
  <li>The request computation can be payed for</li>
  <li>The output of the computation is output, and have the post verified</li>
</ol>
