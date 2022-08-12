.gallery {
  @media screen and (max-width: 767.98px) {
    background-image: linear-gradient(to bottom,
        #FFF5F6 29%,
        #ffffff 29%,
        #ffffff 71%);
  }

  @media screen and (min-width: 768px) and (max-width: 1199.98px) {
    background-image: linear-gradient(to bottom,
        #FFF5F6 56%,
        #ffffff 56%,
        #ffffff 44%);
  }

  @media screen and (min-width: 1200px) {
    background-image: linear-gradient(to bottom,
        #FFF5F6 29%,
        #ffffff 29%,
        #ffffff 71%);
  }
  
 .gallery {
 @include respond-to('medium'){
  background: linear-gradient(
    to bottom,
    #fff5f6 0%,
    #fff5f6 19%,
    #ffffff 19%,
    #ffffff 100%,
    #ffffff 100%,
    #ffffff 100%
  );}

  @include respond-to('medium') {
    padding-top: 60px;
    padding-bottom: 60px;
    background: linear-gradient(
      to bottom,
      #fff5f6 0%,
      #fff5f6 57%,
      #ffffff 57%,
      #ffffff 100%,
      #ffffff 100%,
      #ffffff 100%
    );
  }
  @include respond-to('large') {
    padding-top: 120px;
    padding-bottom: 120px;

    background: linear-gradient(
      to bottom,
      #fff5f6 0%,
      #fff5f6 66%,
      #ffffff 66%,
      #ffffff 100%,
      #ffffff 100%,
      #ffffff 100%
    );
  }
}


// Colors
$primary-background-color: #ffffff;
$secondary-background-color: #FFF5F6; //About , Contacts, Footer sections
$accent-color: #D41443; //nav hover, logo, button text, titles, etc..
$primary-text-color: #000000;
$primary-inverse-text-color: #ffffff;
$secondary-text-color: #907e82;
$secondary-title-color: #ffa5ba; // Section labels (100% natural, tradition and love, homemade ice cream made etc..)
