<link href='//fonts.googleapis.com/css?family=Roboto+Condensed:300,400,700' rel='stylesheet' type='text/css'>
<link href='//fonts.googleapis.com/css?family=Roboto:100,300,400,700,900' rel='stylesheet' type='text/css'>
<h1>Svensk</h1>
<p class="description">Sverige</p>
<div class="distribution-map">
    <!-- This was broken for a while because imgur :( -->
    <!-- I don't trust this host. Image here if it goes down: https://i.imgur.com/M7aUkuS.png -->
    <img src="http://www.geographicguide.com/europe-maps/images/map-sweden.jpg">
    <!--In the original application, these points are injected with Javascript, but ideally, they'd be injected with a haml loop. Because I'm hardcoding content, I'm presenting this as prerendered HTML-->

    <button class="map-point" style="top:70%;left:60%">
        <div class="content">
            <div class="centered-y">
                <h2>Stockholm</h2>
                <p><a href= "https://google.com/">Here you will learn different transportation terms</a></p>
            </div>
        </div>
    </button>

    <button class="map-point" style="top:60%;left:50%">
        <div class="content">
            <div class="centered-y">
                <h2>Dallarna</h2>
                <p><a href= "https://google.com/">Here you will learn basic words to get around Sweden</a></p>
            </div>
        </div>
    </button>
    <button class="map-point" style="top:90%;left:40%">
        <div class="content">
            <div class="centered-y">
                <h2>Malmö</h2>
              <p><a href= "https://google.com/">Here you will visit a cafe and bakery</a></p>
            </div>
        </div>
    </button>
</div>
