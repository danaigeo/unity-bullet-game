<h1>MMI-Group 09: Lena Conle, Valeriia Bubela, Danai Georgiou, Xin Li </h1>

16 July, 2022

**Link to the video presentation: [https://tubcloud.tu-berlin.de/s/Ht9PLyNp5qxHbQS**](https://tubcloud.tu-berlin.de/s/Ht9PLyNp5qxHbQS)**

**Multimodal Interaction**

**Final Project**

**Multimodal Game Introduction**

Our group developed a multimodal game called ‘**Bullet Adventure**’. In this game, a white

little bullet-like player moves, jumps and gains points, while collecting yellow coins.

The user can control the movement and actions of the bullet with keyboard or voice

commands.

The goal of the game is to collect as many coins as possible in a time limit of 60 seconds.

If players cannot collect all the coins before the time is up, the game will show ‘’TIME IS

UP! Your score is: x!’. If they can, the game will show ‘You gathered all the coins in x

seconds!’.

**Modality Selection**

**First Modality: Keyboard Input**

We use the keyboard to finish the game because ……

\-

using a keyboard is a convention in an HCI design, i.e. this is a medium familiar to

people

\-

error-prone

quick reaction time

\-

BUT

\-

high concentration required to perform two and more moves simultaneously pressing

different keys

**Second Modality: Voice Input**

We use voice commands to finish the game because ……

\-

\-

using voice is a natural way of communication for humans

players can concentrate on the screen without the need to look at the keyboard to

press certain buttons

BUT

\-

\-

time delay

errors during ASR

**Modality Fusion and Modality Fission**

**Fusion:**

As long as two commands are not contradicting (e.g. saying forward and pressing ←), all

voice commands and key inputs complement each other.

An example of fusion: We press ‘→’, at the same time say ‘collect’ to collect coins.



<a name="br2"></a> 

MMI-Group 09: Lena Conle, Valeriia Bubela, Danai Georgiou, Xin Li

16 July, 2022

**Fission:**

Out of two implemented modalities, keyboard input is a dominant one. When a user

challenges a game with two contradicting commands, a pressed key is more important for the

following reasons:

\-

\-

\-

it is prove to eventual background noise,

it allows less errors than ASR,

voice commands are sometimes executed with a time delay.

An example of fission: when we press ‘→’ and say ‘back’ at the same time, the bullet will

keep going right.

**Game Instructions**

Your goal is to collect as many coins as possible for the given time. For controlling the

bullet’s movement, you can either use your keyboard or voice commands or a combination of

both. It is important to remember that you need to activate the ‘collect-mode’ either by

pressing ‘K’ on your keyboard or by saying ‘collect’ in order to collect a coin. The

‘collect-mode’ should be activated right before you run through a coin. Only then, you can

collect it. Once the bullet collects a coin, the ‘collect-mode’ is automatically deactivated and

it needs to be re-activated to collect the next coin.

**Keyboard Control**

You can press:

● **‘A’ ‘D’ or ‘←’, ‘→’** to move the bullet left or right

● **‘Space’** to make the bullet jump

● **‘K’** to activate the ‘collect-mode’ for one single coin

**Voice Commands**

You can use the following voice commands:

● **‘forward’** to move the bullet to the right

● **‘back’** to move the bullet to the left

● **‘jump’** to make the bullet jump

● **‘collect’** to activate the ‘collect-mode’ for single point

**Game Code**

The game code link: <https://github.com/valeriiabubela/mmi_sose2022>

Tutorials used:

<https://www.youtube.com/watch?v=pwZpJzpE2lQ>

<https://www.youtube.com/watch?v=Qhm_t46kuM4>

<https://www.youtube.com/watch?v=QbqnDbexrCw>
