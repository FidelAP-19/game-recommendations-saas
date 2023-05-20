---
title: Super Smash Bros. Ultimate
layout: base.njk
pageClass: Nintendo Switch Games
tags:
  - games
  - switch
---

<div class="games-header">
  <h1>Nintendo Switch Games</h1>
</div>
</div>
    <section class="grid-m">
        <article class="card-m">
            <div class="card__content-m">
                <h2 class="card__text-m">Super Smash Bros. Ultimate</h2>
              <p class="card__text-m">
                Super Smash Bros. Ultimate is an action-packed crossover fighting game for the Nintendo Switch. Players can battle it out with a massive roster of beloved characters from various gaming franchises, including Mario, Pikachu, Link, and more. With its fast-paced and chaotic gameplay, along with a variety of multiplayer modes, Super Smash Bros. Ultimate offers exhilarating and competitive matches that bring friends and family together for epic gaming sessions.
              </p>
              <ul>
                <li><strong>Developer(s):</strong> Bandai Namco Studios, Sora Ltd.</li>
                <li><strong>Publisher(s):</strong> Nintendo</li>
                <li><strong>Series:</strong> Super Smash Bros.</li>
                <li><strong>Platform(s):</strong> Nintendo Switch</li>
                <li><strong>Release:</strong> December 7, 2018</li>
                <li><strong>Genre(s):</strong> Fighting</li>
                <li><strong>Mode(s):</strong> Single-player, Multiplayer</li>
              </ul>
            </div>
          </article>
          <article class="card-m">
          <figure class="img-container">
            <div class="card__img-m"><img src="/images/game-main-3.png" alt="Super Smash Bros. Ultimate"></div>
            <figcaption class="img-caption">
               Photo from <a href="https://www.flickr.com/photos/antdude3001/29124067107">flickr</a>
             </figcaption>
          </figure>
          </article>
     </section>
    <div class="game_reviews">
      <h3><strong>Reviews</strong></h3>      <p>
        <strong><i>"SuperSuper Smash Bros. Ultimate’s title alone promises the biggest, best and most complete Smash Bros. to date. Yet the word “ultimate” can also be read not as an enthusiastic superlative, but merely as a coda to the franchise, a blunt culmination of its design. This is the ultimate Smash Bros. because its scope is so massive that it’s hard to imagine adding anything else."<a href="https://www.polygon.com/reviews/2018/12/6/18128504/super-smash-bros-ultimate-review-nintendo-switch" target="_blank" rel="noopener noreferrer"></i></strong> -View full Polygon review</a>
      </p>
      <p>   
        <strong><i>"Super Smash Bros. Ultimate is exactly what its name implies: it’s the ultimate incarnation of Nintendo’s now 20-year-old brawler series. It’s a celebration of Smash Bros. as a whole, filled with more fighters and levels than ever before, and packed to the gills with over 1000 more characters from all across gaming. “Everyone is here!” may have started out as just another tagline, but it’s one that Nintendo has impressively backed up, and it’s made Ultimate the definitive Smash Bros. game for a long time to come. Add a 20+ hour single-player mode with full-on boss fights and huge world maps and it’s easy to get lost in Ultimate. Super Smash Bros. Ultimate had a lot to live up to with that name, but it has undoubtedly done just that."<a href="https://www.ign.com/articles/best-nintendo-switch-games-2" target="_blank" rel="noopener noreferrer"></i></strong> - View full IGN review</a>
      </p>
      <p>
        <strong><i>"Super Smash Bros. Ultimate isn’t just a great fighting game – it’s a love letter to all things gaming. The game’s massive 74-character roster mixes mainstays like Mario, Donkey Kong and Pikachu with newcomers like Splatoon’s Inkling, Metroid’s Ridley, Castlevania’s Simon Belmont and Metal Gear’s Solid Snake, allowing you to create ridiculous dream matches on more than 100 stages from video game history. Ultimate’s multiplayer options run the gamut from insane 8-player brawls to intense 1-on-1 contests, while its robust, RPG-like Spirits mode offers solo players plenty to sink their teeth into. Whether you’re looking for a great Switch party game or a tight competitive brawler, Super Smash Bros. Ultimate truly lives up to its name as one of the best Nintendo Switch games."<a href="https://www.tomsguide.com/round-up/best-nintendo-switch-games" target="_blank" rel="noopener noreferrer"></i></strong> -View full Tom's Guide review</a>
      </p>
      <p>
        <strong><i>"How does this 'ultimate' version of Smash stack up against the rest? Vocal concerns about past games were actively addressed. Every single fighter from the series is present (even Pichu) and joined by a colossal roster of DLC characters from the annals of gaming (let's not forget that this is the game responsible for bringing Banjo and Kazooie back home to a Nintendo console). The customisability is overwhelmingly vast, and it’s all topped off with super-solid single-player modes to boot. We’re not sure how you could make a more robust or pleasing Smash game. Super Smash Bros. Ultimate truly is the ultimate instalment in the series, and it makes you wonder where Masahiro Sakurai can possibly take this franchise next."<a href="https://www.nintendolife.com/guides/50-best-nintendo-switch-games-so-far?page=5" target="_blank" rel="noopener noreferrer"></i></strong> -View full Nintendo Life review</a>
      </p>
    </div>
    <h3><strong>Review Scores</strong></h3>
    <div class="game_numeric_reviews">
      <div class="game_numeric_review">
        <strong>Electronic Gaming Monthly</strong>
        <p>9.5/10</p>
      </div>
      <div class="game_numeric_review">
        <strong>Destructoid</strong>
        <p>9.5/10</p>
      </div>
      <div class="game_numeric_review">
        <strong>GamePro</strong>
        <p>87/100</p>
      </div>
      <div class="game_numeric_review">
        <strong>IGN</strong>
        <p>9.4/10</p>
      </div>
      <div class="game_numeric_review">
        <strong>Nintendo World Report</strong>
        <p>9/10</p>
      </div>
    </div>
    <h3><strong>Awards</strong></h3>
    <div class="game_awards">
      <div class="game_award">
        <p><strong>Game Critics Award for Best Fighting Game<br>2018</strong></p>
      </div>
      <div class="game_award">
        <p><strong>SXSW Gaming Award for Excellence in Gameplay<br>2019</strong></p>
      </div>
      <div class="game_award">
        <p><strong>Golden Joystick Award for Nintendo Game of the Year<br>2019</strong></p>
      </div>
      <div class="game_award">
        <p><strong>The Game Award for Best Fighting Game<br>2019</strong></p>
      </div>
      <div class="game_award">
        <p><strong>Japan Game Award for Excellence Award<br>2019</strong></p>
      </div>
    </div>
    <section class="Collections">
  <h1>All Switch Games</h1>
  <ul>
    {% for game in collections.switch %}      
      <li><a href="{{game.url}}">{{game.data.title}}</a></li>
    {% endfor %}
  </ul>
  </section>