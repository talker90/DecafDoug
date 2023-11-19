# Contact Us

<div id="backgroundDiv" style="text-align: center; background-image: url('images/contact.svg'); height: 85vh; background-attachment: fixed; background-position: center center; background-repeat: no-repeat; background-size: cover'; margin-bottom: 2em;">
</div>

<script>
    function adjustBackground() {
        var backgroundDiv = document.getElementById('backgroundDiv');
        var width = window.innerWidth || document.documentElement.clientWidth || document.body.clientWidth;

        if (width <= 600) { // Mobile devices
            backgroundDiv.style.backgroundImage = "url('images/contact_cropped.svg')";
            backgroundDiv.style.backgroundAttachment = 'scroll';
            backgroundDiv.style.backgroundSize = 'contain'; // Use contain for mobile
        } else {
            backgroundDiv.style.backgroundImage = "url('images/contact.svg')";
            backgroundDiv.style.backgroundAttachment = 'fixed';
            backgroundDiv.style.backgroundSize = 'cover'; // Use cover for desktop
        }
    }

    window.addEventListener('resize', adjustBackground);
    adjustBackground();
</script>

<div style="text-align: center; margin-bottom: 2em; margin-top: 2em; height: 100vh">
    <iframe src="https://forms.gle/h1AptC5xSjMT9MBS8" style="width: 90%; height: 100%; border: 0; margin: auto;" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
</div>

<div style="text-align: center;">
    <img src="images/if_barista-icons_coffee-bean_889379.svg" width="30"> 
    <img src="images/if_barista-icons_coffee-bean_889379.svg" width="30"> 
    <img src="images/if_barista-icons_coffee-bean_889379.svg" width="30">
</div>

<div style="text-align: center;">
    <a href="" style="color: black; text-decoration: none;"><em>Home</em></a>
</div>