*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

body{
    background:#f5f7fb;
    color:#333;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 8%;
    background:#fff;
    box-shadow:0 2px 10px rgba(0,0,0,.08);
    position:sticky;
    top:0;
    z-index:1000;
}

.logo{
    font-size:28px;
    font-weight:700;
    color:#4f46e5;
}

nav ul{
    display:flex;
    list-style:none;
    gap:25px;
}

nav ul li a{
    text-decoration:none;
    color:#333;
    font-weight:500;
    transition:.3s;
}

nav ul li a:hover{
    color:#4f46e5;
}

.btn{
    padding:10px 22px;
    background:#4f46e5;
    color:#fff;
    border-radius:8px;
    text-decoration:none;
    transition:.3s;
}

.btn:hover{
    background:#3730a3;
}

.hero{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:80px 8%;
    gap:50px;
}

.hero-text{
    flex:1;
}

.hero-text h1{
    font-size:52px;
    line-height:1.2;
    margin-bottom:20px;
}

.hero-text p{
    font-size:18px;
    color:#666;
    margin-bottom:30px;
    line-height:1.8;
}

.hero img{
    width:500px;
    border-radius:20px;
    box-shadow:0 10px 30px rgba(0,0,0,.15);
}

.generator{
    width:85%;
    margin:40px auto;
    background:#fff;
    padding:35px;
    border-radius:15px;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.generator h2{
    margin-bottom:20px;
}

textarea{
    width:100%;
    height:180px;
    padding:15px;
    border:1px solid #ddd;
    border-radius:10px;
    resize:none;
    outline:none;
    font-size:16px;
}

textarea:focus{
    border-color:#4f46e5;
}

select{
    margin-top:20px;
    padding:12px;
    width:220px;
    border-radius:8px;
    border:1px solid #ccc;
}

button{
    padding:12px 25px;
    background:#4f46e5;
    color:#fff;
    border:none;
    border-radius:8px;
    cursor:pointer;
    margin-left:10px;
    transition:.3s;
}

button:hover{
    background:#3730a3;
}

.features{
    padding:80px 8%;
}

.features h2{
    text-align:center;
    margin-bottom:50px;
    font-size:36px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:#fff;
    padding:25px;
    border-radius:15px;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h3{
    margin-bottom:15px;
    color:#4f46e5;
}

.card p{
    color:#666;
    line-height:1.6;
}

footer{
    background:#111827;
    color:#fff;
    text-align:center;
    padding:25px;
    margin-top:60px;
}

@media(max-width:900px){

    nav{
        flex-direction:column;
        gap:15px;
    }

    nav ul{
        flex-wrap:wrap;
        justify-content:center;
    }

    .hero{
        flex-direction:column;
        text-align:center;
    }

    .hero-text h1{
        font-size:38px;
    }

    .hero img{
        width:100%;
        max-width:400px;
    }

    .generator{
        width:95%;
    }

    select,
    button{
        width:100%;
        margin:10px 0;
    }
}
