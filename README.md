
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
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
        <img class="image" src="your_image.jpg" alt="Your Image">
        <div class="overlay">
           <img src="https://instagram.fdla2-1.fna.fbcdn.net/v/t51.2885-15/e35/c73.0.554.554a/s150x150/105044346_127329445667781_2507554452160017737_n.jpg?_nc_ht=instagram.fdla2-1.fna.fbcdn.net&_nc_cat=109&_nc_ohc=Z6GCQyBWc5AAX8UqqUO&oh=10de7d78b17ad97d292104e42b2bbce7&oe=5F175C4E" alt="instagram">
        </div>
    </a>
</div>

</body>
</html>
