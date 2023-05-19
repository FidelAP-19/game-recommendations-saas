---
title: Legend of Zelda Breath of the Wild
layout: base.njk
pageClass: Nintendo Switch Games
tags:
  - games
  - switch
---

<div class="games-header">
  <h1>Nintendo Switch Games</h1>
</div>
    <section class="grid-m">
        <article class="card-m">
            <div class="card__content-m">
                <h2 class="card__text-m">Legend of Zelda: Breath of the Wild</h2>
              <p class="card__text-m">
                Legend of Zelda: Breath of the Wild is a highly acclaimed action-adventure game exclusively available on the Nintendo Switch. Set in the vast kingdom of Hyrule, players assume the role of Link, who wakes up from a deep slumber to face the ancient evil known as Calamity Ganon. Featuring a sprawling open world, Breath of the Wild encourages exploration as players traverse diverse landscapes, from lush forests to towering mountains. The game provides players with complete freedom to approach quests and challenges in any order they choose. With its innovative gameplay mechanics, players can climb almost any surface, glide through the air with a paraglider, and utilize a vast array of weapons and abilities. The dynamic weather system and realistic physics add depth and immersion to the gameplay experience. Breath of the Wild captivates players with its stunning art style, awe-inspiring environments, and a richly crafted storyline. It has received widespread acclaim for its open-ended gameplay, memorable characters, and the sense of adventure it instills in players. Legend of Zelda: Breath of the Wild is a must-play game that has solidified its place as one of the greatest entries in the beloved Legend of Zelda franchise.
              </p>
              <ul>
                <li><strong>Developer(s):</strong> Nintendo EPD</li>
                <li><strong>Publisher(s):</strong> Nintendo</li>
                <li><strong>Series:</strong> The Legend of Zelda</li>
                <li><strong>Platform(s):</strong> Nintendo Switch, Wii U</li>
                <li><strong>Release:</strong> March 3, 2017</li>
                <li><strong>Genre(s):</strong> Action-adventure</li>
                <li><strong>Mode(s):</strong> Single-player</li
              </ul>
            </div>
          </article>
          <article class="card-m">
          <figure class="img-container">
            <div class="card__img-m"><img src="/images/game-main-2.png" alt="Legend of Zelda: Breath of the Wild"></div>
            <figcaption class="img-caption">
               Photo from <a href="https://www.flickr.com/photos/douglastofoli/27905049221">flickr</a>
             </figcaption>
             </figure>
          </article>
     </section>
    <div class="game_reviews">
    <h3>Reviews</h3>
      <p>
        <strong><i>"The Legend of Zelda: Breath of the Wild was a landmark release, both for its franchise and Nintendo. It was the first time that Nintendo truly took on the open-world genre, and by arriving late to the party it embraced the strengths from top-of-the-class games while also forging its own unique identity. This game was a revolution for the series, but the Legend of Zelda essence is still there — its soul remains, and the end result is captivating. After years of following the same old template, Nintendo bravely took Zelda in a new direction, and delivered an absolute triumph which still has us regularly revisiting its iteration of Hyrule. Breath of the Wild forged a new and exciting path ahead and we cannot wait to see where it takes the series."<a href="https://www.nintendolife.com/guides/50-best-nintendo-switch-games-so-far?page=5" target="_blank" rel="noopener noreferrer"></i></strong> -View full Nintendo Life review</a>
      </p>
      <p>   
        <strong><i>"The Legend of Zelda: Breath of the Wild sets you loose in a massive, gorgeous open world, where you can battle through dungeons, solve puzzles, paraglide around the skies or simply cook some food. Breath of the Wild redefines what an open-world game could be, with a truly explorable Hyrule in which every mountain is climbable and every hidden path leads to a new adventure (you can even bee-line it to the boss if you're so inclined. With memorable boss battles, tons of challenging puzzle shrines, a gorgeous art style and some of the most dynamic combat in the series, there's good reason many consider BoTW to be the best Zelda game of all time."<a href="https://www.tomsguide.com/round-up/best-nintendo-switch-games" target="_blank" rel="noopener noreferrer"></i></strong> -View full Tom's Guide review</a>
      <p>
        <strong><i>"And lastly, the ultimate Best Nintendo Switch game is The Legend of Zelda: Breath of the Wild. Let’s face it, the Zelda series was long overdue for a major change, and The Legend of Zelda: Breath of the Wild offers an unparalleled sense of freedom and scale in the palm of your hand. Now widely considered one of the best games of all time, Breath of the Wild tells an epic story, as you glide, cook, and battle your way across a beautifully ruined version of Hyrule. It helped reinvigorate The Legend of Zelda in a way that fans had only dreamt of, easily propelling it to the number one spot on our list and in our hearts."<a href="https://www.ign.com/articles/best-nintendo-switch-games-2" target="_blank" rel="noopener noreferrer"></i></strong> -View full IGN review</a>
      </p>
      <p>
        <strong><i>"Breath of the Wild opens with series hero Link awakening in a dark cavern. A mysterious disembodied voice guides him to a tablet that has a passing resemblance to both the Switch and Nintendo's maligned Wii U controller. The tablet helps to navigate this version of Hyrule — the fantasy realm that has long been the heart of Zelda adventures. As you learn in the very early parts of the game, a century ago, powerful evil destroyed much of the world, allowing nature to reclaim castles, and littering the land with abandoned machines of war. People still exist, in small towns and stables, but much of Hyrule is beset by hordes of monsters who have bivouacked into the hills. This is a dangerous place. Naturally, your job is to set things right."<a href="https://www.theverge.com/2017/3/2/14787082/the-legend-of-zelda-breath-of-the-wild-review" target="_blank" rel="noopener noreferrer"></i></strong> -View full The Verge review</a>
      </p>
    </div>
  <section class="Collections">
  <h1>All switch games</h1>
  <ul>
    {% for game in collections.switch %}      
      <li><a href="{{game.url}}">{{game.data.title}}</a></li>
    {% endfor %}
  </ul>
  </section>