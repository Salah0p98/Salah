<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social Media Links</title>
    <style>
        /* General Settings */
        body {
            font-family: Arial, sans-serif;
            direction: rtl;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        section {
            padding: 20px;
        }

        h1 {
            font-size: clamp(24px, 5vw, 36px); /* Flexible size */
            margin-bottom: 20px;
        }

        /* Link Styling */
        .social-links {
            display: flex;
            flex-direction: column;
            gap: 15px; /* Space between links */
            align-items: center; /* Center the links */
        }

        a {
            display: block; /* Links displayed one below the other */
            text-decoration: none;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: clamp(16px, 2.5vw, 20px); /* Flexible font size */
            color: white;
            font-weight: bold;
            transition: transform 0.3s ease, background-color 0.3s ease;
            width: 70%; /* Flexible width */
            max-width: 400px; /* Maximum width */
            text-align: center; /* Center align text */
        }

        a:hover {
            transform: scale(1.05); /* Scale effect on hover */
        }

        /* Facebook Custom Color */
        a.facebook {
            background-color: #3b5998;
        }

        a.facebook:hover {
            background-color: #2d4373; /* Darker color on hover */
        }

        /* Instagram Custom Color */
        a.instagram {
            background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
        }

        a.instagram:hover {
            filter: brightness(1.1); /* Lighten color on hover */
        }

        /* TikTok Custom Color */
        a.tiktok {
            background-color: #000000;
        }

        a.tiktok:hover {
            background-color: #00f5d4; /* Special color on hover */
        }

        /* WhatsApp Custom Color */
        a.whatsapp {
            background-color: #25d366; /* Official WhatsApp color */
        }

        a.whatsapp:hover {
            background-color: #128C7E; /* Change color on hover */
        }
    </style>
</head>
<body>
    <section>
        <h1>Social Media Links</h1>
        <div class="social-links">
            <!-- Facebook Link -->
            <a 
                href="https://www.facebook.com/profile.php?id=100079059007422" 
                target="_blank" 
                class="facebook">
                Facebook
            </a>
            
            <!-- Instagram Link -->
            <a 
                href="https://www.instagram.com/sala.h_marrakchi/profilecard/?igsh=cW1jZXp2ZTRlbGE=" 
                target="_blank" 
                class="instagram">
                Instagram
            </a>

            <!-- TikTok Link -->
            <a 
                href="https://www.tiktok.com/@your_username" 
                target="_blank" 
                class="tiktok">
                TikTok
            </a>

            <!-- WhatsApp Link -->
            <a 
                href="https://wa.me/+212690207071" 
                target="_blank" 
                class="whatsapp">
                WhatsApp
            </a>
        </div>
    </section>
</body>
</html>
