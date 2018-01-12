# walk in square

demo use of mobile geo/positional/gps/compass apis

# research

          /*
          //Check for iOS property
          if (event.webkitCompassHeading) {
            //Rotation is reversed for iOS
            targetAlpha = -targetAlpha;
            alpha = -alpha;
            //compass.style.WebkitTransform = 'rotate(-' + alpha + 'deg)';
            //arrow.style.WebkitTransform = 'rotate(-' + targetAlpha + 'deg)';
          } else { //non iOS
            webkitAlpha = alpha;
            if(!window.chrome) {
              //Assume Android stock (this is crude, but good enough for our example) and apply offset
              webkitAlpha = alpha-270.0;
              webkitTargetAlpha = targetAlpha-270.0;
            }
          }

          document.getElementById('compassValue').innerHTML = alpha;
          */
