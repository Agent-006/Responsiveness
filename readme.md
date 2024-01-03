🔥Responsive website using HTML and CSS🔥


🎯 Understanding Units ✅


🌟 px --> pixel is fixed\
🌟 % --> percentage is what percent of the parent element\
🌟 vw, vh --> viewport width - gives width with respect
                                to the whole screen and\
               &nbsp;viewport height - gives height with respect 
                                 to the whole screen\
🌟 vmax, vmin --> viewportMax - Changes the size with
                                respect to the maximum 
                                size of the screen.\
                &nbsp;viewportMin - Changes the size with
                                 respect to the minimun 
                                 size of the screen.\
🌟 em, rem --> em determines the size with respect to it's
                parent.\
            &nbsp;rem determines the size with respect to the
                root(HTML). 1 root = 16pixels


🎯 Layout of website ✅

🌟 absolute vs flex ?

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