---
title: World of Warcraft
layout: base.njk
pageClass: PC Game
tags:
  - game
  - pc
---

<div class="games-header">
  <h1>PC Games</h1>
</div>
  <section class="grid-m">
        <article class="card-m">
            <div class="card__content-m">
                <h2 class="card__text-m">World of Warcraft</h2>
              <p class="card__text-m">
                World of Warcraft (WoW) is a legendary PC game that redefined the MMORPG genre. Set in the fantasy realm of Azeroth, players create unique characters and embark on thrilling quests, battle fierce monsters, and interact with a vast community of players. With its immersive world, diverse races and classes, and constant updates, WoW offers an unparalleled online gaming experience for adventurers of all kinds.
              </p>
              <ul>
                <li><strong>Developer(s):</strong> Blizzard Entertainment</li>
                <li><strong>Publisher(s):</strong> Blizzard Entertainment</li>
                <li><strong>Series:</strong> Warcraft</li>
                <li><strong>Platform(s):</strong> Microsoft Windows, macOS</li>
                <li><strong>Release:</strong> AU/NA: November 23, 2004, EU: February 11, 2005</li>
                <li><strong>Genre(s):</strong> Massively multiplayer online role-playing</li>
                <li><strong>Mode(s):</strong> Multiplayer</li>
              </ul>
            </div>
          </article>
          <article class="card-m">
            <div class="card__img-m">
            <figure class="img-container">
              <img src="/images/game-main-6.png" alt="World of Warcraft">
              <figcaption class="img-caption">
               Photo from <a href="https://snl.no/World_of_Warcraft">snl.no</a>
             </figcaption>
             </figure>
            </div>
          </article>
  </section>
    <div class="game_reviews">
    <h3><strong>Reviews</strong></h3>      <p>
        <strong><i>"Nearly two decades after its initial release, World of Warcraft is still one of the biggest names in online gaming. Most MMO players cut their teeth on this massive title and it has remained hugely influential throughout multiple expansions and re-releases over the years. WoW might not be the only name in MMOs anymore, but it is still one of the best PC-exclusive games you’ll find."<a href="https://www.gamepur.com/guides/the-ten-best-pc-exclusive-games-of-all-time" target="_blank" rel="noopener noreferrer"></i></strong> -View full Gamepur review</a>
      </p>
      <p>   
        <strong><i>"While this MMO phenom has pretty much been memorable since its release in 2004, the release of WoW Classic reminds fans just how amazing the original version of this Blizzard epic was, even surpassing some of the glitzy RPGs of the modern era. This game borrowed from Everquest in terms of its dynamic system of upgrades, huge scale, and lavish fantasy landscapes. Yet, Blizzard improved and honed the social element with its accessible system of raiding and grouping up in highly-populated zones. At the same time, WoW offers great versatility by allowing for tons of solo quests and dungeon crawling as well."<a href="https://gamerant.com/pc-games-cant-play-console/#sim-city-3000" target="_blank" rel="noopener noreferrer"></i></strong> -View full Game Rant review</a>
      </p>
      <p>
        <strong><i>"Though massively multiplayer online role-playing games have been around for years, it has taken this long for the genre's breakthrough hit to finally emerge. Here is the online role-playing game you should play, no matter who you are. This is because World of Warcraft brings out all the best aspects of this style of gaming, if not many of the best aspects of gaming in general. It also features many of the specific characteristics that have made Blizzard Entertainment's previous games so entertaining, memorable, long-lasting, and successful. Of course, the company's past track record did not guarantee that World of Warcraft could have turned out this well. Such high quality simply cannot be expected, nor should it be missed."<a href="https://www.gamespot.com/reviews/world-of-warcraft-review/1900-6114072/" target="_blank" rel="noopener noreferrer"></i></strong> -View full GameSpot review</a>
      </p>
      <p>
        <strong><i>"When Blizzard first announced that it was working on a massively multiplayer online game (MMO), the first thought that ran through my mind was "Why? Blizzard has no experience in this area. What can they bring that's going to be fresh, new, or different?" It's not until I began seriously playing the final version of World of Warcraft, though, that I realized just how foolish a question that was. Blizzard's particular genius has never been in breaking new ground; it's watching the mistakes other people make and learning from them. Blizzard games have the cache they do because they're polished and refined until they gleam. That, in a nutshell is the essential brilliance of World of Warcraft. It takes the essence of the MMO experience, breaks it down into its component parts, and plays up all the fun elements while actively minimizing the boring or tedious aspects. World of Warcraft is the MMO that nearly everybody can enjoy, and is a shining example of the game developer's art."<a href="http://pc.gamespy.com/pc/world-of-warcraft/571585p1.html" target="_blank" rel="noopener noreferrer"></i></strong> -View full Game Spy review</a>
      </p>
    </div>
    <h3><strong>Review Scores</strong></h3>    <div class="game_numeric_reviews">
      <div class="game_numeric_review">
        <strong>1Up.com</strong>
        <p>A</p>
      </div>
      <div class="game_numeric_review">
        <strong>Edge</strong>
        <p>9/10</p>
      </div>
      <div class="game_numeric_review">
        <strong>Game Informer</strong>
        <p>9.5/10</p>
      </div>
      <div class="game_numeric_review">
        <strong>PC Zone</strong><p>95%</p>
      </div>
      <div class="game_numeric_review">
        <strong>GamePro</strong>
        <p>4.5/5</p>
      </div>
    </div>
    <h3><strong>Awards</strong></h3>    <div class="game_awards">
      <div class="game_award">
        <p><strong>Technology and Engineering Emmy Award for Outstanding Achievement in Video Gaming Technology and Applications<br>2008</strong></p>
      </div>
      <div class="game_award">
        <p><strong>VGX Award for Best PC Game<br>2005</strong></p>
      </div>
      <div class="game_award">
        <p><strong>VGX Award for Best RPG<br>2005</strong></p>
      </div>
      <div class="game_award">
        <p><strong>VGX Award for Most Addictive Video Game<br>2005</strong></p>
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