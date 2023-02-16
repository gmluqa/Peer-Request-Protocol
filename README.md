<h1>
CAPTCHA_SOLVE is a peer 2 peer puzzle solving platform 🧩
</h1>

<h2>Initial plan</h2>

<p>I came up with this idea when filling out captcha's to use sites, what if I could just have the puzzle be automated instead?</p>

<p>
This repository is quite literally that, I am going to code it as they say "a lo guarro" (that means messily in Spanish) but be hopeful about the fact that we do end up delivering on a proof-of-concept, and with some luck, a minimal-viable-product. Don't expect this repository to be super clean, I am starting this as a solo contributor.
</p>

<p>For a proof-of-concept goal of this technology, the goal will be emitting an action on the web forum 4chan, starting a "thread".
</p>

<h2>How the POC will be demonstrated 🤷</h2>
It will fulfill this action with the simple x step process:

<div>
<ol>
  <li>Interface, where the user inputs what they would want in a thread.
</li>
  <li>The user filling out the input and paying another peer to fulfil a captcha puzzle, solve and compute.
</li>
  <li>????
</li>
  <li>PROFIT!!!
</li>
</ol>
</div>

<h2>User interface 💻️</h2>

<img alt="image of the MVP of the visual interface" src="./diagrams/MVP_visual_interface.png"></img>

<p>This UI prototype will allow any peer to fill out any request and execute this computation in a puzzle-agnostic way.</p>

<p>The method of incentivization of which this peer solving this puzzle will act, is by accepting a form of monetary recompense, there is no better solution to this problem than involving any cryptocurrency with low tx fees, for purposes of the POC, we have simply decided to go with fantom(FTM)</p>

<h2>Incentivisation Mechanism 🪙</h2>

<img alt="image of the incentivisation mechanism" src="./diagrams/MVP_Incentives_mechanism.png"></img>

<div>The POC will be marked as a success if the following things happen:
<ol>
  <li>Oracles can verify if a post was made inside of an SLA</li>
  <li>The contract can recieve the response from the oracles that the post was made</li>
  <li>The interface exists on the contract level and can be called by anyone</li>
  <li>The request computation can be payed for</li>
  <li>The output of the computation is output, and have the post verified</li>
</ol>
</div>

<h1>Why would this project be revolutionary? 🐉</h1>

<div>One may not understand the value of delivering on this POC, but the applications of such a technology are the following:
<ul>
  <li>Incentivizing peers to solve captchas 'en masse' on a determined website</li>
  <li>Incentivizing for prime number discovery, verified incentivization of unlocking an unknown prime number</li>
  <li>Incentivizing guesswork of secrets</li>
  <li>Puzzle or computation resolution</li>
    <li>Incentivizing peers to deliver chatGPT messages inside of an SLA (doesn't even require a captcha, just requires verification of the output and an SLA)</li>
  <li>Incentivization for fulfilment of tasks</li>
</ul>
</div>

<p>As you can probably tell from the examples, many of them have to do with proving something that may be unverified to the user, and in order to solve this, the output must be verified as authentic.</p>

<p>For this reason, we must, while remaining in a blockchain world, access information from the web, and verify that it was verifiably emitted, trying to resolve this dilema on-chain is impossible, since the blockchain will never know what's going on out there on the internet.</p>

<p>We can prove this real-world information using a decentralized oracle, however, the difficulty is knowing whether a decentralized oracle service provider such as Chainlink can provide a verification of website data and emit to the smart contract that it was indeed, authentic</p>

<p>Because of this, we are starting with phase 1, the oracle and the contract level, if the oracle can be set up as to accept this verification, then we're in business.</p>

<h1>PHASE 1: THE ORACLE AND THE CONTRACT LEVEL</h1>

<h2>THE ORACLE 🌐</h2>

<p>We are reaching out to the team at Chainlink to discuss whether such a DON (decentralized oracle network) is able to be set-up and also fulfil this verification, whilst being cost effective. If the answer is no, we will have to build our own oracle mechanism that relies somehow on the $CAPTCHA token.</p>

<p>Honestly chainlink is hard to set up for such a custom job, so for now we're going to make our own oracle, that will be embedded into the token, and will be validated by other peers (more bobs!)</p>

<p>Here is how the oracle mechanism works:</p>

<img alt="image of the MVP of the oracle mechanism" src="./diagrams/MVP_Oracle.png"></img>
