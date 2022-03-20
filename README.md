# 104RegistrationForm
Registration form with full stack

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Before and After sudo selectors</title>
    <link href="https://fonts.googleapis.com/css2?family=Sansita+Swashed:wght@500&display=swap" rel="stylesheet">
</head>
<style>
    body{
       
        font-family: 'Sansita Swashed', cursive;
        background-color: rgb(243, 4, 191);
        margin: 0;
        padding: 0;
        color: white;
    }
    .navigation{
        display: flex;
    }
    section{
        /* border: 2px solid red; */
        text-align: center;
        height: 400px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    li{
        padding: 23px;
        list-style: none;
    }
    h1{
        font-size: 3rem;
    }
    p{
        text-align: center;
    }
    /* +++++++++++++++++++++++++++++++++++ important starts+++++++++++++++++*/
    header::before{
        background: url('https://images.unsplash.com/photo-1601701119495-d6e39b664001?ixlib=rb-1.2.1&q=80&fm=jpg&crop=entropy&cs=tinysrgb&w=1080&fit=max') no-repeat center center/cover;
        content: "";
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
        bottom: 0;
        z-index: -5;
        opacity: 6;
    }
/* +++++++++++++++++++++++++++++++++++++++++++important end++++++++ */

</style>
<body>
    <header>
    <nav>
        <ul class="navigation">
            <li>Home</li>
            <li>About</li>
            <li>Contact Us</li>
            <li>More</li>

        </ul>
    </nav>
</header>
    <section>
        <h1>This is Aazaad-Adarsh Website</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque praesentium maxime voluptates aperiam eum. Ullam temporibus, nulla officia blanditiis inventore vel? Nemo sed dolores et doloremque reiciendis porro corporis, assumenda voluptatibus corrupti! Iusto, quia ipsam!</p>
    </section>
    
</body>
</html>
