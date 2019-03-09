# CSS-code-for-Piano
html {
    font-size: 10px;
    background: url(https://musicglue-user-app-p-4-p.s3.amazonaws.com/originals/3104e8a5-73dd-fa9c-31b8-395ee3e124d4) bottom center;
    background-size: cover;
}

body,html {
    margin: 0;
    padding: 0;
    font-family: sans-serif;
}

.keys {
    display: flex;
    flex: 1;
    min-height: 100vh;
    align-items: center;
    justify-content: center;
}

.key {
    display: table;
    border-radius: .5rem;
    font-size: 1.5rem;
    padding: 1rem .5rem;
    transition: all .07s ease;
    text-align: center;
}

.white {
    margin: 0.05rem;
    border: .2rem solid rgb(76, 49, 30);
    width: 10rem;
    height: 40rem;
    color: white;
    background-image: radial-gradient(white, #fbf5ee);
    box-shadow: inset 0 0 2rem #7b6349;
    text-shadow: 0 0 .5rem rgb(46, 30, 0);
    z-index: 1;
}

.black {
    position: absolute;
    border: .2rem solid rgb(0, 0, 0);
    width: 5rem;
    height: 23rem;
    color: white;
    background-image: radial-gradient(#5d5d5d, black);
    box-shadow: inset 0 0 0 0.1rem #ffffff70;
    text-shadow: 0 0 .5rem rgb(0, 0, 0);
    z-index: 2;
}

.sharp-pos-top {
    margin-top: -9rem;
}

.c-sharp {
    margin-left: -35rem;
}

.d-sharp {
    margin-left: -23rem;
}

.g-sharp {
    margin-left: 11.5rem;
}

.a-sharp {
    margin-left: 23rem;
}

.playing-white {
    transform: scale(0.98);
    box-shadow: inset 0 0 2rem rgb(37, 28, 10);
    background-image: linear-gradient(#efeae5, #d2c6b8);
}

.playing-black {
    transform: scale(0.98);
    box-shadow: inset 0 0 0 0.1rem rgb(0, 0, 0);
    background-image: radial-gradient(black, #404040);
}

kbd {
    display: table-cell;
    vertical-align: bottom;
    font-size: 4rem;
}
