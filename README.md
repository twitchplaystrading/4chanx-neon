Add the code below to your CSS section on 4chan-x. The color is set to purple with font size 14pt.
![alt text](https://github.com/twitchplaystrading/4chanx-neon/blob/69b7e28e1c9e8974923aad980d2292d4608951d5/Screenshot_20220223_173204.png)

--------------------
```
/* Board title rice */

:root.tomorrow div.boardTitle {
    font-weight: 400 !important;
}

:root.tomorrow .dialog {
    background: rgba(0,0,0,0.7)
}

:root.fixed:not(.gallery-open) #header-bar:not(:hover) {
    background: rgba(0,0,0,0.7) !important
}

:root.tomorrow .catalog-stats {
    color: rgb(0, 238, 255) !important;
}

:root.tomorrow div.post blockquote.postMessage {
font-family: 'Arial';
font-size: 14pt;
}

:root.tomorrow .catalog-thread.watched .catalog-thumb{
    border: 4px solid red
}

:root.tomorrow.highlight-own .yourPost > .reply {
    border: 2px #ea00ff solid !important;
    box-shadow: 0 0 20px #ea00ff !important;        
}

:root.tomorrow.highlight-you .quotesYou > .reply {
    border: 2px #0059ff solid !important;
    box-shadow: 0 0 20px #0059ff !important;
}

:root.tomorrow .qphl{
    outline: 2px solid rgba(#8000ff, 0.2) !important;
}

:root.tomorrow .quotelink, .deadlink{
    color: #8000ff !important;
}

:root.tomorrow div.reply{
    background: rgba(0,0,0.9,0.45) !important; 
    backdrop-filter: blur(10px) !important;
    border: 2px #8000ff solid !important;
    box-shadow: 0 0 20px #8000ff !important;
    border-radius: 20px !important;
    padding-right: 10px !important;
    padding-left: 10px !important;
    margin-top: 10px;
}

:root.tomorrow .prettyprint{
    background: rgba(0,0,0,0.1);
    backdrop-filter: blur(10px);
}
:root.tomorrow .catalog-post.catalog-post{
    background: rgba(0,0,0,0.5);
    backdrop-filter: blur(10px);

}
#overlay, #qp, #ihover, #navlinks, .fixed #header-bar, :root.float #updater, :root.float #thread-stats, #qr {
    background: rgba(0,0,0,0.1) !important;
    backdrop-filter: blur(10px) !important;
    border: 1px #8000ff2a solid !important
}
:root.tomorrow.catalog-hover-expand .catalog-container:hover > .post {
    background: rgba(0,0,0,0.99) !important;
    backdrop-filter: blur(10px) !important;
    border: 1px #8000ff79 solid !important
}
:root.tomorrow .qr-link {
    background: rgba(0,0,0,0.1) !important;
    backdrop-filter: blur(10px) !important;
    border: 1px #8000ff79 solid !important
}
:root.tomorrow #qr > form {
    width: 100%;
}
:root.tomorrow body{
    /*I self host the server that serves my background image*/
    background-image: url(YOUR_BACKGROUND_IMAGE_HERE);
    background-size:cover;
    background-attachment: fixed !important;
    background-repeat: no-repeat;
    background-position: center;
}
:root.tomorrow blockquote>span.quote{
    color: #0065ad !important;
}

:root.tomorrow a, a:visited {
    color: #8000ff!important;
    text-decoration: none;
}
```
