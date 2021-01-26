<!DOCTYPE html>
<html>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<style>
body {
      background-color: #000000;
}
body,h1,h5 {font-family: "Raleway", sans-serif}
body, html {height: 100%}
.bgimg {
  background-image: url(https://github.com/iamekm/iamekm.github.io/blob/master/EK-spectro-01a.jpg?raw=true);
  min-height: 100%;
  background-position: center;
  background-size: cover;
}
</style>
<body>

<div class="bgimg w3-display-container w3-text-white">
  <div class="w3-display-middle w3-xxlarge">
    <p><b>|Sound Making Space|</b></p>
  </div>
  <div class="w3-display-topleft w3-container w3-xlarge">
    <p><button onclick="document.getElementById('menu').style.display='block'" class="w3-button w3-black">EVENTS</button></p>
    <p><button onclick="document.getElementById('contact').style.display='block'" class="w3-button w3-black">CONTACT</button></p>
    <p><button onclick="document.getElementById('info').style.display='block'" class="w3-button w3-black">INFO</button></p>
  </div>
  <div class="w3-display-bottomleft w3-container">
    <p class="w3-small">A Bartlett, UCL Doctoral Network</p>
    <p class="w3-small"><a href="http://soundmakingspace.com/">2017-2000</a></p>
  </div>
</div>

<!-- Menu Modal -->
<div id="menu" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom">
    <div class="w3-container w3-black w3-display-container">
      <span onclick="document.getElementById('menu').style.display='none'" class="w3-button w3-display-topright w3-large">x</span>
      <h1>5th March @17:00 GMT</h1>
    </div>
    <div class="w3-container">
      <h5><b> JONATHAN TYRRELL</b></h5>
      <h5>Radical Intersubjectivity: Architecture in the Expanded Sonic Field</h5>
      <h5><a href="https://www.eventbrite.co.uk/e/radical-intersubjectivity-architecture-in-the-expanded-sonic-field-tickets-138426181435/">LINK</a></h5>
    </div>
    <div class="w3-container w3-black">
      <h1>12th March @17:00 GMT</h1>
    </div>
    <div class="w3-container">
      <h5><b>NINA GARTHWAITE, ELEANOR MCDOWALL + RAZIA JORDAN</b></h5>
      <h5>Curating Sound</h5>
      <h5><a href="https://www.eventbrite.co.uk/e/curating-sound-tickets-138426374011">LINK</a></h5>
    </div>
    <div class="w3-container w3-black">
      <h1>19th March @17:00 GMT</h1>
    </div>
    <div class="w3-container">
      <h5><b>LISA HALL</b></h5>
      <h5>Acts Of Air</h5>
      <h5><a href="https://www.eventbrite.co.uk/e/acts-of-air-tickets-138426522455">LINK</a></h5>
    </div>
  </div>
</div>

<!-- Contact Modal -->
<div id="contact" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom">
    <div class="w3-container w3-black">
      <span onclick="document.getElementById('contact').style.display='none'" class="w3-button w3-display-topright w3-large">x</span>
      <h1>Contact</h1>
    </div>
    <div class="w3-container">
      <p><b>Contact Emma-Kate + Paul:</b></p>
      <p><a href="mailto:soundmakingspace@gmail.com?subject=Hello">EMAIL</a></p>
      <p><b>Follow Us:</b></p>
      <p><a href="https://www.instagram.com/soundmakingspace/">INSTAGRAM</a> </p>
      <p><a href="https://twitter.com/sms_bartlett">TWITTER</a> </p>
      <p><a href="https://www.facebook.com/groups/soundmakingspace">FACEBOOK</a> </p>
      </form>
    </div>
  </div>
</div>

</body>
</html>

<!-- Info Modal -->
<div id="info" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom">
    <div class="w3-container w3-black">
      <span onclick="document.getElementById('info').style.display='none'" class="w3-button w3-display-topright w3-large">x</span>
      <h1>Info</h1>
    </div>
    <div class="w3-container">
      <p>|SOUND MAKING SPACE| is a UCL, Bartlett Doctoral Network, co-founded in 2017 by Bartlett School of Architecture PhD students Ruth Bernatek and Merijn Royaards. The network has now grown to include a number of internal researchers and designers, as well as associate members and external collaborators. Architect <a href="https://paulbavister.com/">Paul Bavister</a> and Composer/Architect <a href="https://www.ekm.works/">Emma-Kate Matthews</a> are curating the current series of events for the SMS network. </p>
      <p>Our aim is to convene a diverse group of researchers and practitioners who think about and engage with architecture and space through sound. We believe that sound has the capacity to disclose new ways to design for, and think about architecture and our urban environment. We draw upon expertise both from within and beyond the field of architecture, inviting speakers with various academic, professional and practice backgrounds, including musicology, anthropology, computing, engineering, mathematics, performance studies, planning, and acoustics. Our research seminars and events have brought together international sound artists, composers, performers, architects and curators to share and discuss their research, experience and expertise.</p>
      <p>Details of our current projects, initiatives, upcoming seminars, club nights and events can be found on our events tab. Seminar sessions are open to all, and FREE.</p>
      </form>
    </div>
  </div>
</div>
</body>
</html>
