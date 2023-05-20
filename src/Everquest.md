---
title: Everquest
layout: base.njk
pageClass: PC Game
tags:
  - game
  - pc
---
<div class="games-header">
  <h1>PC Games</h1>
</div>
</div>
  <section class="grid-m">
        <article class="card-m">
            <div class="card__content-m">
                <h2 class="card__text-m">Everquest</h2>
              <p class="card__text-m">
                EverQuest is a classic PC game that revolutionized the MMORPG genre. Set in the fantasy world of Norrath, players create characters, embark on epic quests, and battle formidable foes in a vast and immersive online world. With its rich lore, diverse races and classes, and cooperative gameplay, EverQuest offers an unforgettable adventure for fans of role-playing games.
              </p>
              <ul>
                <li><strong>Developer(s):</strong> 	Verant Interactive, 989 Studios</li>
                <li><strong>Publisher(s):</strong> NA: Sony Online Entertainment, EU: Ubi Soft</li>
                <li><strong>Platform(s):</strong> Microsoft Windows</li>
                <li><strong>Release:</strong> NA: March 16, 1999, EU: April 28, 2000</li>
                <li><strong>Genre(s):</strong> Massively multiplayer online role-playing game</li>
                <li><strong>Mode(s):</strong> Multiplayer</li>
              </ul>
            </div>
          </article>
          <article class="card-m">
          <figure class="img-container">
            <div class="card__img-m"><img src="/images/game-main-5.png" alt="Everquest"></div>
            <figcaption class="img-caption">
               Photo from <a href="https://www.flickr.com/photos/slprofr/1542303944">flickr</a>
             </figcaption>
             </figure>
          </article>
     </section>
    <div class="game_reviews">
    <h3><strong>Reviews</strong></h3>      <p>
        <strong><i>"From the thick woodlands of Kelethin to the lunar landscapes of Luclin, Everquest's locales are lavish and vast; and continue to grow. It's tough to beat the satisfaction and fun this game grants in spades, with its range of cool monsters, sweet loot, and fruitful quests that invite players to team up. The best part? It's become a free-to-play game, making it all the more worth diving into this awesome journey."<a href="https://gamerant.com/pc-games-cant-play-console/?newsletter_popup=1#star-wars-the-old-republic" target="_blank" rel="noopener noreferrer"></i></strong> -View full Game Rant review</a>
      </p>
      <p>   
        <strong><i>"EverQuest, released in 1999, was one of the first massively multiplayer online role-playing games (MMORPGs) and is considered a pioneer in the genre. The game was set in the fantasy world of Norrath, and it allowed players to create characters and embark on quests, interact with other players, and form groups to take on more challenging content. The game’s graphics were impressive for its time, and the world was vast and immersive, being one of the first 3D MMOs. It was a revolutionary game that set the standard for many of the MMORPGs that came after it, and it continues to be enjoyed by many players even in 2023."<a href="https://mmorpg.gg/everquest-review/" target="_blank" rel="noopener noreferrer"></i></strong> -View full MMORPG.GG review</a>
      </p>
      <p>
        <strong><i>"EverQuest is one of the most popular online role-playing games: play the black knight, the reclusive wizard, or the crafty rogue in this immersive and mythic world of stellar fantasy. And with never before seen, state-of-the-art 3D graphics, you'll never want to leave the world of EverQuest."<a href="http://pc.gamespy.com/pc/everquest/" target="_blank" rel="noopener noreferrer"></i></strong> -View full Game Spy Review</a>
      </p>
      <p>
        <strong><i>"While its graphics set it apart right away, EverQuest is going to last, not because it's pretty, but because it plays well. On the technical side, gameplay is smooth and mostly lag-free even over a 56K modem. Lag is rarely problematic even when it happens (you'll find yourself complaining about the long loading times between regions instead), though the occasional "lag death" has been witnessed. Otherwise, EverQuest offers dozens of different race and class combinations, which is perhaps the most enticing feature in the game. You can play a comparatively mundane fantasy character - a dwarf warrior or a human cleric, for instance - or you can choose something more exotic, like a dark elf necromancer or a troll shadowknight. The race you choose will critically affect your experience of the game, since most every race has a unique hometown, which you'll have to stick close to for the first several weeks of play. The class you choose is just as important, and all of them play differently, and most of them are fun. You'll want to try several combinations before you commit to one, but you can't realistically cultivate more than one or two characters."<a href="https://www.gamespot.com/reviews/everquest-review/1900-2535859/" target="_blank" rel="noopener noreferrer"></i></strong> -View full GameSpot review</a>
      </p>
    </div><h3><strong>Review Scores</strong></h3>    <div class="game_numeric_reviews">
      <div class="game_numeric_review">
        <strong>GameRevolution</strong>
        <p>A-</p>
      </div>
      <div class="game_numeric_review">
        <strong>GameSpot</strong>
        <p>8.4/10</p>
      </div>
      <div class="game_numeric_review">
        <strong>PC Gamer</strong>
        <p>86%</p>
      </div>
      <div class="game_numeric_review">
        <strong>Next Generation</strong>
        <p>5 out of 5 Stars</p>
      </div>
      <div class="game_numeric_review">
        <strong>IGN</strong>
        <p>8.4/10</p>
      </div>
    </div>
    <h3><strong>Awards</strong></h3>    <div class="game_awards">
      <div class="game_award">
        <p><strong>Technology & Engineering Emmy Award for Outstanding Achievement in Video Gaming Technology and Applications<br>2008</strong></p>
      </div>
      <div class="game_award">
        <p><strong>The Academy of Interactive Arts and Sciences for Online Game of the Year<br>1999</strong></p>
      </div>
      <div class="game_award">
        <p><strong>Game Developers Choice Online Awards Hall of Fame award<br>2011</strong></p>
      </div>
    </div>
    <section class="Collections">
  <h1>Other PC Games</h1>
  <ul>
    {% for game in collections.pc %}      
      <li><a href="{{game.url}}">{{game.data.title}}</a></li>
    {% endfor %}
  </ul>
  </section> 
