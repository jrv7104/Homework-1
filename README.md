# Code Refactor Challenge

This is a code refactor project, and this was the first assignment I received from my coding and web development boot camp from Washington University.

There were 3 major things I noticed about this page that I was able to address.

1. The digital marketing meeting file was not present when the page was originally opened. I placed the photo above the div class="hero" and widened the photo to 100% to fill out the page while keeping the proportions together.

2. While the image was improved, it left a significant gap between the next sections. I went in the .hero section in the css file and reduced the height to 10px. That eliminated the empty space while keeping other elements intact.

3. The last thing I updated was the three tabs on the top right. With some help I discovered that it would't take me to the search engine optimization section when I cicked on it, but the other two tabs worked. With that help I discovered that the search engine optimization was listed as a class element, not ID element. Once that element was changed the tab worked like the other two.

After reviewing HTLM more, I updated it after I graduated from the program with more semantic code. Instead of having classes of header and footer I just used those tags and updated the tags in the CSS file in order for it to work properly. I also added nav tags to make it a little more clear.