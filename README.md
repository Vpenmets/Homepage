# Homepage
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Clickable Image</title>
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
</style>
</head>
<body>

<div class="container">
    <a href="https://www.instagram.com/umarylandigem/">
        <img class="image" src="your_image.jpg" alt="Your Image">
        <div class="overlay"></div>
    </a>
</div>

</body>
</html>
