---
title: Forza Horizon 5
layout: base.njk
tags: 
   - navItem
   - xbox
pageClass: home
---


<div class="games-header">
  <h1>Xbox Games</h1>
</div>
    <section class="grid-m">
        <article class="card-m">
            <div class="card__content-m">
                <h2 class="card__text-m">Forza Horizon 5</h2>
              <p class="card__text-m">Forza Horizon 5 is currently the best racing game out at this moment. The game takes place a fictional Mexico and boasts of a large open map filled with challenges. The games’ ability to customize your car and share car tuning with other player just add to its stunning graphics. The incredible map design which includes volcanos and swamps alongside the variety in cars to pick from is what make it the best racing game out. With the constant update of content being added to the game I don’t see it slowing down in popularity anytime soon.</p>
              <ul>
                  <li><strong>Developer(s):</strong> 	Playground Games</li>
                <li><strong>Publisher(s):</strong> Xbox Game Studios</li>
                <li><strong>Platform(s):</strong> Xbox Series S and X</li>
                <li><strong>Release:</strong> November 1 ,2021</li>
                <li><strong>Genre(s):</strong> Racing</li>
                <li><strong>Mode(s):</strong> Single player and Multiplayer</li>
              </ul>
            </div>
          </article>
          <article class="card-m">
          <figure class="img-container">
            <div class="card__img-m"><img src="/images/game-main-11.png" alt=""></div>
            <figcaption class="img-caption">
               Photo from <a href="https://www.flickr.com/photos/194744165@N02/51861231541">flickr</a>
             </figcaption>
             </figure>
          </article>
     </section>
     <div class="game_reviews">
    <h3>Reviews</h3>
      <p>
        <strong><i>"Forza Horizon 5 is, without a doubt, one of the best racing games of all time you can play right now and certainly one of the best looking on the Xbox Series X. Set in a fictional version of Mexico, Forza Horizon 5 boasts the largest open-world map of any of the Forza Horizon games, and there is no shortage of races and challenges to complete. There are also numerous ways to customize your cars by swapping engines, drivetrains, and body kits."<a href="https://gaminggorilla.com/best-xbox-series-x-exclusive-games/" target="_blank" rel="noopener noreferrer"></i></strong> -View full Gaming Gorilla review</a>
      </p>
        <p>
        <strong><i>"The Forza Horizon series is undoubtedly the best racer going at the moment, and this latest entry's jaunt to Mexico continues the hot streak. The South American country hosts plenty of thrilling locations to screech through, from drifting around a volcano to skidding around swamps, with the fleet of cars you race in as eye-meltingly fast as you'd hope for. "<a href="https://www.gamesradar.com/xbox-exclusives/" target="_blank" rel="noopener noreferrer"></i></strong> -View full Games Radar review</a>
      </p>
       <p>
        <strong><i>"Without question, Forza Horizon 5 is one of the best racing games there is, not just on Xbox. The Series X enhanced version runs excellently, too."<a href="https://www.digitaltrends.com/gaming/best-xbox-series-x-exclusives/?amp" target="_blank" rel="noopener noreferrer"></i></strong> -View full Digital Trends review</a>
      </p>
      </div>
  <section class="Collections">
  <h1>All xbox games</h1>
  <ul>
    {% for game in collections.xbox %}      
      <li><a href="{{game.url}}">{{game.data.title}}</a></li>
    {% endfor %}
  </ul>
  </section>

     