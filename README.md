
<!DOCTYPE html>
<html lang="en">
<head>
<div align ="left">
<a href="https://www.instagram.com/umarylandigem/" HEIGHT=50<img src= https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" 
HEIGHT=50></a>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Clickable Image with Instagram Logo</title>
<style>
    .container {
        position: relative;
        width: 100%;
        max-width: 500px; /* Adjust as needed */
    }
    .image {
        width: 100%;
        height: auto;
    }
    .overlay {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        background-color: transparent; /* Change to desired color */
        opacity: 0; /* Initially transparent */
        cursor: pointer;
    }
    .overlay:hover {
        opacity: 0.5; /* Change opacity on hover */
    }
    .instagram-logo {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: 50px; /* Adjust the size of the logo as needed */
        height: auto;
        display: none; /* Initially hidden */
    }
    .overlay:hover .instagram-logo {
        display: block; /* Show the logo on overlay hover */
    }
</style>
</head>
<body>

<div class="container">
    <a href="https://www.instagram.com/umarylandigem/">
        <img class="HEIGHT=50<img src= https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" 
HEIGHT=50></a>>
        <div class="overlay">
            <img class="instagram-logo" src="instagram_logo.png" alt="Instagram Logo">
        </div>
    </a>
</div>

</body>
</html>
