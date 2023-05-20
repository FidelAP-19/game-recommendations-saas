---
title: God of War Ragnarok
layout: base.njk
pageClass: PS Game
tags: 
 - game
 - ps
---

<div class="games-header">
  <h1>PS Games</h1>
</div>
<section class="grid-m">
      <article class="card-m">
            <div class="card__content-m">
                <h2 class="card__text-m">God of War: Ragnarok</h2>
              <p class="card__text-m">
                God of War was one of the most anticipated games of 2022 and was the perfect sequel for its 2018 release. The game had high expectations and surpassed them due to its great visuals, and story. The gameplay is immersive, and the characters are well written and memorable. The entire game is an incredible adventure filled with memorable events such as amazing boss fights, beautiful soundtracks and a brilliant storyline</p>
              <ul>
                 <li><strong>Developer(s):</strong> Santa Monica Studios</li>
                <li><strong>Publisher(s):</strong> Sony Online Entertainment</li>
                <li><strong>Platform(s):</strong> Playstation 4 and 5</li>
                <li><strong>Release:</strong> November 9, 2022</li>
                <li><strong>Genre(s):</strong> Action-Adventure</li>
                <li><strong>Mode(s):</strong> Single player</li>
              </ul>
            </div>
          </article>
          <article class="card-m">
          <figure class="img-container">
            <div class="card__img-m"><img src="/images/game-main-7.png" alt=""></div>
            <figcaption class="img-caption">
               Photo from <a href="https://www.flickr.com/photos/scarlizz/28584625208">flickr</a>
             </figcaption>
             </figure>
          </article>
     </section>
       <div class="game_reviews">
    <h3><strong>Reviews</strong></h3>
      <p>
        <strong><i>"Although Elden Ring beat it for Game of the Year, God of War Ragnarok stands out as one of the most anticipated PS5 games of 2022 and has certainly lived up to the hype, making it our number-one pick."<a href="https://gaminggorilla.com/best-ps5-exclusive-games/" target="_blank" rel="noopener noreferrer"></i></strong> -View full Gaming Gorilla review</a>
      </p>
        <p>
        <strong><i>"God of War Ragnarok improves on 2018's already excellent God of War in every possible way — which says it all, really. It's a massive adventure spanning all nine realms of Norse mythology, and the game's jaw-dropping scope is probably its greatest asset. Just when you think you've seen it all, Ragnarok pops up with something completely new and exciting, time and time again. An immense experience, polished to near perfection. One of PlayStation Studios' best works."<a href="https://www.pushsquare.com/guides/best-ps5-exclusive-games?page=3" target="_blank" rel="noopener noreferrer"></i></strong> -View full Push Square review</a>
      </p>
       <p>
        <strong><i>"Rarely does a game manage to meet everybody's expectations, particularly when the expectations in question are as high as the ones for God of War Ragnarok were in the build-up to the game's release. However, the developers absolutely smashed it, providing the perfect sequel to the series' 2018 installment as well as a fitting conclusion to Kratos and Atreus' epic adventures through Norse Mythology."<a href="https://gamerant.com/ps5-playstation-5-best-console-exclusive-games/#the-last-of-us-part-1" target="_blank" rel="noopener noreferrer"></i></strong> -View full Game Rant review</a>
      </p>
      <p>
        <strong><i>"Rarely does a game manage to meet everybody's expectations, particularly when the expectations in question are as high as the ones for God of War Ragnarok were in the build-up to the game's release. However, the developers absolutely smashed it, providing the perfect sequel to the series' 2018 installment as well as a fitting conclusion to Kratos and Atreus' epic adventures through Norse Mythology."<a href="https://gamerant.com/ps5-playstation-5-best-console-exclusive-games/#the-last-of-us-part-1" target="_blank" rel="noopener noreferrer"></i></strong> -View full Game Rant review</a>
      </p>
      </div>
      <h3><strong>Review Scores</strong></h3>
    <div class="game_numeric_reviews">
      <div class="game_numeric_review">
        <strong>Electronic Gaming Monthly</strong>
        <p>5 out of 5 Stars</p>
      </div>
      <div class="game_numeric_review">
        <strong>Game Informer</strong>
        <p>9.5/10</p>
      </div>
      <div class="game_numeric_review">
        <strong>IGN</strong>
        <p>10/10</p>
      </div>
      <div class="game_numeric_review">
        <strong>The Telegraph</strong>
        <p>5 out of 5 Star</p>
      </div>
      <div class="game_numeric_review">
        <strong>VideoGamer.com</strong>
        <p>10/10</p>
      </div>
    </div>
    <h3><strong>Awards</strong></h3>
    <div class="game_awards">
      <div class="game_award">
        <p><strong>Golden Joystick Award for Most Wanted Game<br>2020</strong></p>
      </div>
      <div class="game_award">
        <p><strong>Titanium Award for Game of the Year<br>2022</strong></p>
      </div>
      <div class="game_award">
        <p><strong>The Game Award for Best Action/Adventure<br>2022</strong></p>
      </div>
      <div class="game_award">
        <p><strong>New York Game Award for Herman Melville Award for Best Writing in a Game<br>2023</strong></p>
      </div>
      <div class="game_award">
        <p><strong>British Academy Games Award for Animation<br>2023</strong></p>
      </div>
    </div>
      <section class="Collections">
  <h1>All PS Games</h1>
  <ul>
    {% for game in collections.ps %}      
      <li><a href="{{game.url}}">{{game.data.title}}</a></li>
    {% endfor %}
  </ul>
  </section>