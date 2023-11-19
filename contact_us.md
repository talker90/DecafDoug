<div id="backgroundDiv" style="text-align: center; background-image: url('images/contact.svg'); height: 85vh; background-attachment: fixed; background-position: center center; background-repeat: no-repeat; background-size: cover';">
</div>

<script>
    function adjustBackground() {
        var backgroundDiv = document.getElementById('backgroundDiv');
        var width = window.innerWidth || document.documentElement.clientWidth || document.body.clientWidth;

        if (width <= 600) { // Mobile devices
            backgroundDiv.style.backgroundImage = "url('images/contact.svg')";
            backgroundDiv.style.backgroundAttachment = 'scroll';
            backgroundDiv.style.backgroundSize = 'contain'; // Use contain for mobile
        } else {
            backgroundDiv.style.backgroundImage = "url('images/contact_cropped.svg')";
            backgroundDiv.style.backgroundAttachment = 'fixed';
            backgroundDiv.style.backgroundSize = 'cover'; // Use cover for desktop
        }
    }

    window.addEventListener('resize', adjustBackground);
    adjustBackground();
</script>

We'd love to hear from you! Whether you have feedback, questions, or suggestions, please feel free to reach out.

<div style="text-align: center; margin-bottom: 2em; margin-top: 2em;">
    <iframe src="https://forms.gle/h1AptC5xSjMT9MBS8" sstyle="width: 100%; height: 600px; max-height: 100vh; border: 0; margin: auto;" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
</div>

Thank you for taking the time to reach out to us. Your input is greatly appreciated!

