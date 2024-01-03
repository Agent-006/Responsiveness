🔥Responsive website using HTML and CSS🔥


🎯 Understanding Units ✅

🌟 px --> pixel is fixed\

    target_element {
        font-size: 12px;
    }

🌟 % --> percentage is what percent of the parent element\

    target_element {
        font-size: 12%;
    }

    /* OR */

    target_element {
        height: 50%;
        width: 100%;
    }

🌟 vw, vh --> viewport width - gives width with respect
                                to the whole screen and\
               &nbsp;viewport height - gives height with respect 
                                 to the whole screen\

    target_element {
        height: 100vh;
        width: 100vw;
    }

    /* this will take size with respect to the width of the screen */
    target_element {
        font-size: 6vw; 
    }

    /* this will take size with respect to the height of the screen */
    target_element {
        font-size: 6vh; 
    }


🌟 vmax, vmin --> viewportMax - Changes the size with
                                respect to the maximum 
                                size of the screen.\
                  viewportMin - Changes the size with
                                 respect to the minimun 
                                 size of the screen.\

    target_element {
        font-size: 7vmax;
    }

    target_element {
        font-size: 7vmin;
    }


🌟 em, rem --> em determines the size with respect to it's
                parent.\
               rem determines the size with respect to the
                root(HTML). 1 root = 16pixels

    /* 1em means - 1 * <|pixel size of parent|> */
    target_element {
        font-size: 1em;
    }

    /* 1rem means - 1 * <|pixel size of root|> */
    target_element {
        font-size: 1rem;
    }

🎯 Layout of website ✅

🌟 absolute vs flex ?

--> Using position: absolute will make it hard to be responsive later.

    target_element {
        position: absolute;
    }

--> Always preffer using flexbox to make it easy make the website more responsive.

    target_element {
        display: flex;
    }


🎯 flexbox ✅

🌟 Display flex 

    target_element {
        display: flex; /* by default it is block */
    }


🌟 aligning items in x and y axis

    target_element {
        display: flex;
        align-item: center; /* to center with respect to the cross-axis( y-axis )*/
        justify-content: center; /* to center with respect to the main-axis(x-axis)*/
    }


🌟 flex direction

    target_element {
        display: flex;
        flex-direction: column; /* default row */
    }


🌟 flex wrap

    target_element {
        display: flex;
        flex-wrap: wrap; /* this wraps the element accordingly */ 
    }

🎯 Css Media Queries ✅

🌟 min height, min width
🌟 min width, max width

    /* this will be applied to all devices below 600px in width */
    @media (max-width:600px) {
        target_element {
            background-color: royalblue;
            border-radius: 50%;
        }
    }


🔑 Key points to keep in mind to make website responsive

1️⃣ CSS Flexbox
2️⃣ CSS Units
3️⃣ Responsive Typography
4️⃣ Mobile-First Approach
5️⃣ Flexible Images and Media

📌 Practice! Practice! Practice!