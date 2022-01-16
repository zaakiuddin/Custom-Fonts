# Custom-Fonts
In this repository i have showed how you can add  custom fonts to make your website stand out .
In css before body tag use 

@font-face {
    font-family: " your font name ";
    src: url(font/_your font path_) format("truetype");
    
    then specify in your tags or para like this
    
    h1 {
    font-size: 6em;
    font-family: "your font name", sans-serif;  // use sans-serif because let say if your font didnt load for any reason then sens-serif will load in place of that.
    font-weight: bold;
}


