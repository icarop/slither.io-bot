<h2>slither.io-bot</h2>
<i>An <s>open</s> source Slither.io client implementation (written in node.js).</i>
<a href="https://slibot.io/en/">Get bots from here</a>

<h4>Change log</h4>
<ul>
  <li><b>19/04/16:</b> Started programming the client in node.js and started to understand the current game client.</li>
  <li><b>20/04/16:</b> Downloaded the newer game client and started writing 3 new handlers.</li>
  <li><b>21/04/16:</b> Created the current github repository.</li>
  <li><b>21/04/16:</b> Implemented HTTP proxy support.</li>
  <li><b>21/04/16:</b> Update servers to the new slither.io update.</li>
  <li><b>22/04/16:</b> Noticed static variables are traps and are actually being loaded dynamically, adjusted the code to now load the variables dynamically.</li>
  <li><b>23/04/16:</b> Currently handling food spawning and food being eaten.</li>
  <li><b>23/04/16:</b> Created a new function so the snake could be moved around.</li>
  <li><b>23/04/16:</b> Added a new event handlers "snakeMoved", "foodSpawned", "foodEaten", "snakeMoved" and renamed one of them.</li>
  <li><b>23/04/16:</b> Created a new file on the repository showing an example of using proxies(HTTP).</li>
  <li><b>24/04/16:</b> Noticed "snakeAppeared" handler should get the current snake who spawned X and Y .</li>
  <li><b>24/04/16:</b> Getting other snake's X and Y completed reflected in the picture.</li>
  <li><b>01/05/16:</b> Added a new event handler "codeUpdate".</li>
  <li><b>01/05/16:</b> Trying to make the snake move doesn't work and instead uses the rubbish server control.</li>
  <li><b>01/05/16:</b> Started working on disabling the server control over the snake spawned by the client currently checking the headers.</li>
  <li><b>27/05/16:</b> <s>Started working on the bot again, the bot is now confirmed to be a <b>public</b> bot, maybe an API.</s></li>
  <li><b>28/05/16:</b> This project has been abandoned, the code for the bot is <b>ONLY</b> going to be private, sorry to the people who got happy.</li>
</ul>

<h6>Bot is currently being developed on in private, and will <b>NEVER</b> be public.</h6>
<h6>Project completed.</h6>

<img src="http://i.imgur.com/k2ygqtJ.png" /><br>
<i>Latest running version of the client.</i><br>

<img src="http://i.imgur.com/p8RPPkD.png" /><br>
<i>Showing other snakes movements instead of (0, 0).</i><br>

<img src="http://i.imgur.com/jcxth8u.png" /><br>
<i>The current bot can load the snakes which "appear" around it.</i><br>

<img src="http://i.imgur.com/xbXGbqW.png" /><br>
<i>Found my bot after a little search time, changed the name to make it easier to find :).</i><br>

<img src="http://i.imgur.com/tQtGbrv.png" /><br>
<i>Using proxies to create loads of bots on a single server.</i><br>
