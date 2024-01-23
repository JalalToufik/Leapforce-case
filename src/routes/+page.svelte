<section>
    <p>
        Label
    </p>
    
    <h1>
        Mandatory title about the 
        <span>call-to-action </span>
        here
    </h1>
    
    <p>
        Optional body copy goes here.
    </p>
    
    <button class="optional-btn"> 
        Optional button 
        <svg width="14" height="14" viewBox="0 0 14 14" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M6 1L12 7L6 13" stroke="#BF564D" stroke-width="1.5" stroke-miterlimit="4.62023"/>
            <path d="M0 7L12 7" stroke="#BF564D" stroke-width="1.5" stroke-miterlimit="4.62023" stroke-linejoin="round"/>
        </svg>
    </button>
    
</section>

<section>
    <ul>
        <li>
            <div>
                <p>Title</p>
                <p>Supporting text about the call-to-action goes here.</p>
            </div>
            <button>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 6L18 12L12 18" stroke="white" stroke-width="1.5" stroke-miterlimit="4.62023"/>
                    <path d="M6 12L18 12" stroke="white" stroke-width="1.5" stroke-miterlimit="4.62023" stroke-linejoin="round"/>
                </svg>
            </button>
        </li>
        <li>
            <div>
                <p>Title</p>
                <p>Supporting text about the call-to-action goes here.</p>
            </div>
            <button>
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M12 6L18 12L12 18" stroke="white" stroke-width="1.5" stroke-miterlimit="4.62023"/>
                    <path d="M6 12L18 12" stroke="white" stroke-width="1.5" stroke-miterlimit="4.62023" stroke-linejoin="round"/>
                </svg>
            </button>
        </li>
    </ul>
</section>

<style>

    @font-face {
        font-family: 'GTAlpina-Light';
        src: url('/fonts/GTAlpina-Light.otf') format('otf');
    }

    @font-face {
        font-family: 'TT-Pro-Medium';
        src: url('/fonts/TT-Pro-Medium.otf') format('otf');
    }

    * {
        box-sizing: border-box;

    }

    section:nth-of-type(1){
        padding: 1em;
        display: flex;
        flex-direction: column;
    }

    section:nth-of-type(2){
        display: flex;
        flex-direction: row;
        justify-content: center;
    }

    p, h1 {
        text-align: center;
    }

    h1{
        font-family: 'GTAlpina-Light', sans-serif;
        font-size: 2.3em;
        margin: 0 auto;
        padding: .5em 0;
        max-width: 10em;
    }

    h1 span{
        font-family: 'Times New Roman', sans-serif;
        font-weight: 200;
    }

    section p:nth-of-type(1){
        font-size: .9em;
    }

    p{
        color: #39494D;
        margin: 0;
        font-family: 'TT-Pro-Medium', sans-serif;
    }

    button{
        background-color: transparent;
        border: none;
    }

    .optional-btn{
        color: #BF564D;
        display: flex;
        justify-content: center;
        align-items: center;
        text-align: center;
        margin: 1.2em 0;
        text-decoration: none;
    }

    .optional-btn svg{
        margin-left: .5em;
    }

    ul{
        padding: 0;
        margin: 0;
        display: flex;
        justify-content: center;
        flex-wrap: wrap;
        gap: 1em;
        list-style: none;
    }

    li{
        background-image: url(/couple.png);
        background-size: cover;
        background-position: center;
        background-repeat: no-repeat;
        width: 20.9em;
        display: flex;
        justify-content: space-between;
        align-items: flex-end;
        height: 15.75em;
        border-radius: 5px;
        padding: 1em
    }

    li p{
        color: white;
        text-align: left;
        margin: 0;
    }

    li p:nth-of-type(1){
        padding-bottom: 1em;
        font-size: 1.37em;
    }


    li p:nth-of-type(2){
        color: #AAA8A6;
    }

    li button{
        background-color: transparent;
        border: solid 2px #AAA8A6;
        border-radius: 5px;
        width: 2.5em;
        height: 2.5em;
    }

    li button svg{
        position: relative;
        top: 1px;
        left: -4px;
    }


    @media (min-width: 43.75em) {

        ul{
            justify-content: center;
            flex-direction: column;
        }

    }

    /* Tablet */
    @media (min-width: 50em) {

        section{
            padding: 2em;
        }

        h1{
            font-size: 2.6em;
            max-width:  12em;
        }

        p, button{
            font-size: 1.18em;
        }

        ul{
            flex-direction: row;
        }

        li{
            width: 22em;
            height: 29em;
        }

        li p:nth-of-type(1){
            font-size: 1.75em;
        }

        li button svg{
            left: 0px;
        }

    }

    /* Desktop */
    @media (min-width: 90em){

        li{
            width: 40em;
            height: 32em;
        }

    }



</style>