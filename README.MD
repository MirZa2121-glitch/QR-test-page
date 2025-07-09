# Hello

# Varriables bottom for QR layout 

// Color
--first-color: hsl(212, 45%, 89%);
--second-color: hsl(216, 15%, 48%);
--third-color: hsl(218, 44%, 22%);

// Container
--container: 1200px;
--padding: 0 15px;
--margin: 0 auto;

// QR
--qr-width: 300px;
--qr-height: 400px;

// Font size
--default-font-size: 15px;
--first-font-size: 15px;
--second-font-size: 22px;
--third-font-size: 26px;
--four-font-size: 14px;

# Used default CSS and HTML 
# In reset.css used body color var(--first-color)

# Default reset for CSS

* {
    box-sizing: border-box;
    font-family: 'Outfit', sans-serif;
    text-decoration: none;
    list-style-type: none;
    padding: 0;
}

h1, h2, h3, h4, h5, h6 {
    padding: 0;
    margin: 0;
}

html, body {
    overflow-x: hidden;
    overflow-y: auto;
}

html {
    scroll-behavior: smooth;
}

body {
    background-color: hsl(212, 45%, 89%);
}

