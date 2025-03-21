<div class="blog--grid">
        <div class="blog--1">
            <div class="blog--img1">
                <div class="blog--img">
                    <img src="https://niotech-nextjs.vercel.app/_next/image?url=%2Fassets%2Fimages%2Fblog%2FblogThumb3_1.jpg&w=640&q=75" alt="">
                </div>
                <span class="absolute-date">
                    <span id="number">20</span>
                    <span id="date">June</span>
                </span>
            </div>

           

            <div class="blog--tittle">
                <span>By Admin</span>
                <span>Technology</span>
            </div>

            <div class="blog--header">
                <h2>Regional Managers Time Management</h2>
            </div>
            <button class="btn">Read More</button>
        </div> 

        <div class="blog--1">
            <div class="blog--img"><img src="https://niotech-nextjs.vercel.app/_next/image?url=%2Fassets%2Fimages%2Fblog%2FblogThumb3_1.jpg&w=640&q=75" alt=""></div>

            <span class="absolute-date">
                <span id="number">20</span>
                <span id="date">June</span>
            </span>

            <div class="blog--tittle">
                <span>By Admin</span>
                <span>Technology</span>
            </div>

            <div class="blog--header">
                <h2>Regional Managers Time Management</h2>
            </div>
            <button class="btn">Read More</button>
        </div>    
        <div class="blog--1">
            <div class="blog--img"><img src="https://niotech-nextjs.vercel.app/_next/image?url=%2Fassets%2Fimages%2Fblog%2FblogThumb3_1.jpg&w=640&q=75" alt=""></div>

            <span class="absolute-date">
                <span id="number">20</span>
                <span id="date">June</span>
            </span>

            <div class="blog--tittle">
                <span>By Admin</span>
                <span>Technology</span>
            </div>

            <div class="blog--header">
                <h2>Regional Managers Time Management</h2>
            </div>
            <button class="btn">Read More</button>
        </div>    
        <div class="blog--1">
            <div class="blog--img"><img src="https://niotech-nextjs.vercel.app/_next/image?url=%2Fassets%2Fimages%2Fblog%2FblogThumb3_1.jpg&w=640&q=75" alt=""></div>

            <span class="absolute-date">
                <span id="number">20</span>
                <span id="date">June</span>
            </span>

            <div class="blog--tittle">
                <span>By Admin</span>
                <span>Technology</span>
            </div>

            <div class="blog--header">
                <h2>Regional Managers Time Management</h2>
            </div>
            <button class="btn">Read More</button>
        </div>    
    </div>







    <!-- ================kjgutvjh============== -->

    @import url('https://fonts.googleapis.com/css2?family=Anybody:ital,wght@0,100..900;1,100..900&family=Heebo:wght@100..900&family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Manrope:wght@200..800&family=Playwrite+NZ+Guides&family=Poppins:wght@300&family=Roboto+Serif:ital,opsz,wght@0,8..144,100..900;1,8..144,100..900&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;

    h1,
    h2,
    h3,
    h4,
    h5,
    h6 {
        color: #fff;
    }

    span {
        color: #7444fd;
    }

    span i {
        color: #fff;
    }

    p {
        color: #9da3b4;
    }

    button {
        color: #fff;
    }

    a {
        text-decoration: none;
    }
}

body {
    background-color: #0f0a2b;
    font-family: "Manrope", sans-serif;
}

img {
    width: 100%;
    height: auto;
}


/* Container */
.box-container {
    width:100%;
    max-width: 1360px;
    margin: 0 auto;
}

.blog--grid {
    display: grid;
    grid-template-columns:repeat(4,1fr);
    gap: 3rem;
    padding: 3rem 2rem;
}

.blog--img img {
    border-radius: .5rem;
    
}

.blog--img1 {
    position: relative;
}


.blog--1 {
    display: flex;
    flex-direction: column;
    align-items: self-start;
    gap: 1.5rem;
    background-color: #663333;
    padding: 2rem 2rem;
    border-radius: .5rem;
}

.absolute-date {
    display: flex;
    flex-direction: column;
    position: absolute;
    bottom: -17px;
    left: 15px;
    width: 15%;

}

.absolute-date #number {
    background: #7444fd;
    color: #fff;
    border-radius: 2rem;
    display: flex;
    place-content: center;
}
    
