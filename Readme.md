<h1>MMI-Group 09</h1>

16 July, 2022 - Lena Conle, Valeriia Bubela, Danai Georgiou, Xin Li 

**Link to the video presentation: [https://tubcloud.tu-berlin.de/s/Ht9PLyNp5qxHbQS**](https://tubcloud.tu-berlin.de/s/Ht9PLyNp5qxHbQS)**

<h2> Multimodal Interaction </br> 
Final Project </h2>


<h2> Multimodal Game Introduction </h2>

Our group developed a multimodal game called ‘**Bullet Adventure**’. In this game, a white 

little bullet-like player moves, jumps and gains points, while collecting yellow coins.

The user can control the movement and actions of the bullet with keyboard or voice commands. </br>

The goal of the game is to collect as many coins as possible in a time limit of 60 seconds.

If players cannot collect all the coins before the time is up, the game will show ‘’TIME IS

UP! Your score is: x!’. If they can, the game will show ‘You gathered all the coins in x

seconds!’.

<h2> Modality Selection </h2>

<h3> First Modality: Keyboard Input </h3>

We use the keyboard to finish the game because: </br>

<ul> 
  <li>  using a keyboard is a convention in an HCI design, i.e. this is a medium familiar to
people </li>
<li> error-prone </li> 
<li> quick reaction time </li>
</ul>
<ul> But: </br> 
  <li>high concentration required to perform two and more moves simultaneously pressing
different keys
</li>
  
</ul>

<h3> Second Modality: Voice Input </h3>
We use voice commands to finish the game because: </br>

<ul>
  <li> using voice is a natural way of communication for humans </li>
  <li></li>
  <li>players can concentrate on the screen without the need to look at the keyboard to
press certain buttons</li>
</ul>
<ul> But: </br>
  <li> time delay</li>
  <li> errors during ASR </li>
</ul>

<h3> Modality Fusion and Modality Fission </h3>

**Fusion:** </br>

As long as two commands are not contradicting (e.g. saying forward and pressing ←), all

voice commands and key inputs complement each other. </br>

An example of fusion: We press ‘→’, at the same time say ‘collect’ to collect coins. </br>


**Fission:** </br>

Out of two implemented modalities, keyboard input is a dominant one. When a user

challenges a game with two contradicting commands, a pressed key is more important for the

following reasons: </br>
<ul>
  <li> it is prove to eventual background noise, </li>
  <li> it allows less errors than ASR, </li>
  <li> voice commands are sometimes executed with a time delay. </li>
</ul>


An example of fission: when we press ‘→’ and say ‘back’ at the same time, the bullet will keep going right </br>

<h2> Game Instructions </h2>

Your goal is to collect as many coins as possible for the given time. For controlling the

bullet’s movement, you can either use your keyboard or voice commands or a combination of

both. It is important to remember that you need to activate the ‘collect-mode’ either by

pressing ‘K’ on your keyboard or by saying ‘collect’ in order to collect a coin. The

‘collect-mode’ should be activated right before you run through a coin. Only then, you can

collect it. Once the bullet collects a coin, the ‘collect-mode’ is automatically deactivated and

it needs to be re-activated to collect the next coin.

<h3> Keyboard Control </h3> </br>

You can press: 
<ul>
  <li> <b> ‘A’ ‘D’ or ‘←’, ‘→’ </b> to move the bullet left or right </li>
  <li> <b> ‘Space’ </b> to make the bullet jump </li>
  <li> <b> ‘K’ </b> to activate the ‘collect-mode’ for one single coin </li>
</ul>


<h3> Voice Commands </h3> </br>

You can use the following voice commands:
<ul>
  <li> <b> ‘forward’ </b> to move the bullet to the right</li>
  <li> <b> ‘back’ </b> to move the bullet to the left </li>
  <li> <b> ‘jump’ </b> to make the bullet jump</li>
  <li> <b> ‘collect’ </b> to activate the ‘collect-mode’ for single point</li>
</ul>


<h3> **Game Code** </h3>

The game code link: <https://github.com/valeriiabubela/mmi_sose2022>

Tutorials used: </br>
 <https://www.youtube.com/watch?v=pwZpJzpE2lQ>

<https://www.youtube.com/watch?v=Qhm_t46kuM4>

<https://www.youtube.com/watch?v=QbqnDbexrCw>

