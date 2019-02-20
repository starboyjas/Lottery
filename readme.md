
<h1 align="center" style="background:#990000 color:white " >PROCESS DIAGRAM OF LOTTERY APPLICATION</h1>

<center><h3>Simple Lottery</h3></center>
<img src="https://i.imgur.com/ljrrP57.png" width="100%" height="100%" border="5">

<ol>
  <li><b>[System]</b> Set time or Day duration for lottery  </li>
  <li><b>[System]</b> Start lottery</li>
  <li><b>[Users]</b> The users must buy tickets before the ends of lottery duration.</li>
  <li><b>[Smart Contract]</b> If the lottery duration ends,the system will not accept tickets anymore</li>
  <li><b>[System]</b> Draw Lottery</li>
  <li><b>[Smart Contract]</b> Smart Contract will randomize all tickets to generate a winner</li>
  <li><b>[Users]</b> The winner can withdraw prize for the lottery</li>
 </ol>


<hr/>
<center><h3>Recurring Lottery</h3></center>
<img src="https://i.imgur.com/es3QPLq.png" width="100%" border="5">

<ol>
  <li><b>[System]</b> Set Duration</li>
  <li><b>[System]</b> Start lottery</li>
  <li><b>[Smart Contract]</b> Create Rounds</li>
  <li><b>[Users]</b> The users must buy tickets before the ends of lottery duration.</li>
  <li><b>[Smart Contract]</b> If the lottery duration ends,the system will not accept tickets anymore</li>
  <li><b>[Smart Contract]</b> Create Next Rounds </li>
  <li><b>[System]</b> All tickets bought after previous round's duration will moved to next Round</li>
  <li><b>[System]</b>Draw previous round</li>
  <li><b>[Smart Contract]</b> Smart Contract will randomize previous rounds tickets to generate a winner</li>
  <li><b>[Users]</b> The winner can withdraw prize for the lottery</li>
  <li><b>[System]</b> The previous rounds can be  delete after</li>
 </ol>
 
<hr/>
<center><h3>RNG Lottery</h3></center>
<img src="https://i.imgur.com/dHxtauf.png" width="100%"  border="5">
<ol>
  <li><b>[System]</b> Set Ticket and Reveal Deadline</li>
  <li><b>[System]</b> Start lottery</li>
  <li><b>[Users]</b> The users must enter their one secret number ( Commitment ) </li>
  <li><b>[Smart Contract]</b> The smart Contract will encrypt user secret number with their user's address </li>
  <li><b>[Users]</b>User must pay for their secret number ( Pay Commitment )</li>
  <li><b>[Smart Contract]</b>Smart Contract checks ticket deadline</li>
  <li><b>[System]</b> If the system reached ticket deadline,the system will not accept tickets anymore</li>
  <li><b>[Users]</b>User must reveal their secret number</li>
  <li><b>[Smart Contract]</b> Smart Contract checks reveal deadline</li>
 <li><b>[System]</b> If the system reached reveal deadline,All unrevealed commitments will exclude from the lottery </li>
  <li><b>[System]</b> Draw Rounds</li>
    <li><b>[Smart Contract]</b> Smart Contract will randomize ticket numbers to generate a winner</li>
   <li><b>[Users]</b> The winner can withdraw prize for the lottery</li>

 </ol>
 

<hr/>
<center><h3>Poweball Lottery</h3></center>
<img src="https://i.imgur.com/iQdUBLx.png" width="100%"  border="5">

<ol>
  <li><b>[System]</b> Set Time or Day Duration</li>
  <li><b>[System]</b> Start lottery</li>
  <li><b>[Smart Contract]</b> Create Rounds</li>
  <li><b>[Users]</b> The users must buy tickets with 6 numbers before the ends of lottery duration.</li>
    <li><b>[Smart Contract]</b> The smart contract will check if the last number of tickets is less than 27 </li>
  <li><b>[Smart Contract]</b> If the lottery duration ends,the system will not accept tickets anymore</li>
  <li><b>[Smart Contract]</b> Create Next Rounds </li>
  <li><b>[System]</b> All tickets bought after previous round's duration will moved to next Round</li>
  <li><b>[System]</b>Draw previous round</li>
  <li><b>[Smart Contract]</b> Smart Contract will generate random 6 nubmers to select a winner</li>
  <li><b>[Users]</b> The winners can withdraw prize for the lottery</li>
 </ol>
 
 
<hr/>

