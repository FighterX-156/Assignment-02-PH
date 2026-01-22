# Assignment-02-PH
Assignment 02 - TechWave
/* Speech-Card Started */
.Speech-Card{
  align-items: center;
  gap: 25px;
  background-color: #250D44;
  padding: 40px;
  border-radius: 25px;
}
.Meet{
  padding-bottom:  110px ;
}
.Meet h1{
   font-size: 3rem;
   text-align: center;
   margin: 30px 0;
}
.Speech{
   flex-direction: column;
   justify-content: space-between;
   gap: 20px;
}
.Speech h2{
   font-size: 2rem;
   margin-top: 20px;
}
.Speech p{
  font-weight: 200;
}
.Social-Buttons{
  gap: 20px;
}
.S-Button img{
  width: 20px;
}
.S-Button{
  border-radius: 50%;
  border: 1px solid #533C72;
  padding: 20px;
  align-items: center;
  justify-content: center;
}
/* Meet Done */
/* Footer Started */
.Footer{
  background: url(Resources/footer-bg.png);
  background-position: center;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 460px;
  gap: 30px;
}
.Footer-link-list{
list-style: none;gap: 40px;
}

.Footer-link-list li a {
  text-decoration: none;
   font-weight: 200;
}
.F-link{
   align-items: center;
   gap: 10px;
   
}
.Footer p{
   font-weight: 200;
}
/* Footer Done */



<footer class="Footer flex ">
      <span class="Title flex"
          ><h1>Tech</h1>
          <h1 class="Wave">Wave</h1></span>
      <ul class="Footer-link-list flex">
        <li><a href="" class="F-link flex"><img src="Resources/spotify.png" alt="">Spotify</a></li>
        <li><a href="" class="F-link flex"><img src="Resources/apple-podcast.png" alt="">Apple Podcasts</a></li>
        <li><a href="" class="F-link flex"><img src="Resources/youtube-podcast.png" alt="">YouTube </a></li>
        <li><a href="" class="F-link flex"><img src="Resources/twitter.png" alt="">Twitter</a></li>
      </ul>  
       <p>© 2026 TechWave Podcast. All rights reserved.</p>
    </footer