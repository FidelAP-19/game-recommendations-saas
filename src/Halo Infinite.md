---
title: Halo Infinite
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
                <h2 class="card__text-m">Halo Infinite</h2>
              <p class="card__text-m">Halo Infinite, winner of Player’s Voice Award 2021, has helped revitalize a Halo series which first released in 2001. This open world game filled with new mechanics, collectibles and hidden audio logs that add on to the main storyline make this a must play for anyone who is a fan of the Halo series. This game is filled with places to explore and alongside a compelling multiplayer make it a great addition any game library.</p>
              <ul>
                 <li><strong>Developer(s):</strong> 343 Industries</li>
                <li><strong>Publisher(s):</strong> Xbox Game Studios</li>
                <li><strong>Platform(s):</strong> Xbox Series S and X</li>
                <li><strong>Release:</strong> November 15, 2021</li>
                <li><strong>Genre(s):</strong> Shooter</li>
                <li><strong>Mode(s):</strong> Single player and Multiplayer</li>
              </ul>
            </div>
          </article>
          <article class="card-m">
          <figure class="img-container">
            <div class="card__img-m"><img src="/images/game-main-10.png" alt=""></div>
            <figcaption class="img-caption">
               Photo from <a href="https://www.flickr.com/photos/195579570@N07/52074349354">flickr</a>
             </figcaption>
             </figure>
          </article>
     </section>
     <div class="game_reviews">
    <h3>Reviews</h3>
      <p>
        <strong><i>"Halo Infinite is a fresh take on a franchise that has been around since Halo Combat Evolved, which was released in 2001 and has definitely helped revitalize the series.Having taken home the Player’s Voice Award at the 2021 Game Awards, this is one game you won’t want to miss if you are a fan of the originals, and it is available right now on Game Pass!"<a href="https://gaminggorilla.com/best-xbox-series-x-exclusive-games/" target="_blank" rel="noopener noreferrer"></i></strong> -View full Gaming Gorilla review</a>
      </p>
        <p>
        <strong><i>"Halo Infinite might have been years in the making, with some Craig-sized bumps along the way, but by the time it finally hit consoles, fans were rightly wowed by the game's focused and compelling multiplayer alongside the vast open-world that shakes up Halo's single-player story. Not only does this feel like the most vital Halo since 2010's Halo Reach, but the addition of the grapple hook gives Chief a pleasing maneuverability that made firefights even more satisfyingly chaotic. After several years in the wilderness, Master Chief is finally back on top form."<a href="https://www.gamesradar.com/xbox-exclusives/" target="_blank" rel="noopener noreferrer"></i></strong> -View full Games Radar review</a>
      </p>
       <p>
        <strong><i>"Of all the franchises out there, Microsoft is most closely tied with the Halo series. It essentially was the reason to buy the original Xbox when it first launched and pioneered not only the first-person genre on consoles, but revolutionized online multiplayer too. Xbox owes a lot to this franchise, so it makes sense that they would want to keep it alive. Despite being delayed for two years after the Series X and S launched, we finally got our first taste of a brand new Halo game on these upgraded machines in the form of Halo: Infinite.  Split between the free-to-play multiplayer and campaign, this Halo is a little light on content but promises to continue to grow over time. At the core, though, the gameplay is more than enough reason to jump in. This throwback to the classic arena-style shooter is a breath of fresh air in a genre filled with specialists, loadouts, complex abilities, and overpowered builds."<a href="https://www.digitaltrends.com/gaming/best-xbox-series-x-exclusives/?amp" target="_blank" rel="noopener noreferrer"></i></strong> -View full Digital Trends review</a>
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

    