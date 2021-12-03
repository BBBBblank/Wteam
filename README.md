# Wteam
/* 清除浏览器默认边距，
使边框和内边距的值包含在元素的width和height内 */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
header {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 100px;
    z-index: 10;
    background: #5b639c;
}
header .logo {
    position: relative;
    font-size: 1.5em;
    color: #fff;
    text-decoration: none;
    font-weight: 600;
}
header .navigation {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin: 10px 0;
}
header .navigation li {
    list-style: none;
    margin: 0 20px;
}
header .navigation li a {
    text-decoration: none;
    color: #fff;
    font-weight: 600;
    letter-spacing: 1px;
}
header .navigation li a:hover{
    color: #ffed3b;
}
header .search {
    position: relative;
    width: 300px;
    height: 40px;
}
header .search input {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    color: #fff;
    background: transparent;
    outline: none;
    border: 1px solid #fff;
    border-radius: 5px;
    padding: 0 10px 0 45px;
}
header .search input::placeholder {
    color: #fff;
}
header .search .fa-search {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    left: 10px;
    color: #fff;
    border-right: 1px solid #fff;
    padding-right: 10px;
}
.banner {
    background: #eee;
    padding: 200px 100px 100px;
    min-height: 100vh;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.banner .content {
    max-width: 1000px;
}
.banner .content h2 {
    font-size: 2.5em;
    color: #333;
    margin-bottom: 20px;
}
.banner .content p {
    font-size: 1em;
    color: #333;
}
.banner .content a {
    display: inline-block;
    background: #434978;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: 600;
    margin-top: 20px;
}
.banner .image {
    max-width: 500px;
    margin-left: 50px;
}



.title {
    height: 100px;
}

.context_up,
.context_down {
    width: 1500px;
    margin: 0 auto;
}

.box1,
.box2,
.box3,
.box4,
.box5,
.box6 {
    width: 480px;
     
    margin: 10px;
    font-size: larger;
    float: left;
    letter-spacing: 1px;
}

.box1 a {
    text-decoration: none;
    font-weight: 600;
    letter-spacing: 4px;
}
.box1 a h2{
    width: 164px;
    margin: 0 auto;
}
.box1 a p{
    width: 232px;
    margin: 0 auto;
}

.box2 a{
    text-decoration: none;
    font-weight: 600;
    letter-spacing: 4px;
}
.box2 a h2{
    width: 164px;
    margin: 0 auto;
}
.box2 a p{
    width: 279px;
    margin: 0 auto;
}

.box3 a{
    text-decoration: none;
    font-weight: 600;
    letter-spacing: 4px;
}
.box3 a h2{
    width: 164px;
    margin: 0 auto;
}
.box3 a p{
    width: 325px;
    margin: 0 auto;
}

.box4 a{
    text-decoration: none;
    font-weight: 600;
    letter-spacing: 4px;
}
.box4 a h2{
    width: 164px;
    margin: 0 auto;
}
.box4 a p{
    width: 279px;
    margin: 0 auto;
}

.box5 a{
    text-decoration: none;
    font-weight: 600;
    letter-spacing: 4px;
}
.box5 a h2{
    width: 164px;
    margin: 0 auto;
}
.box5 a p{
    width: 279px;
    margin: 0 auto;
}

.box6 a{
    text-decoration: none;
    font-weight: 600;
    letter-spacing: 4px;
}
.box6 a h2{
    width: 164px;
    margin: 0 auto;
}
.box6 a p{
    width: 186px;
    margin: 0 auto;
}

./*屏幕宽度小于991px,改变布局和样式*/
@media screen and (max-width:991px) {
    header {
        padding: 10px 20px;
        flex-direction: column;
    }
    main{
        padding: 10px 20px;
        flex-direction: column;
    }
    .context_down,.context_up {
        padding: 150px 20px 50px;
        flex-direction: column-reverse;
    }
    
    .banner .content h2 {
        font-size: 2em;
    }
}
/*屏幕宽度小于600px,改变布局和样式*/
@media screen and (max-width:600px) {
    header .search {
        width: 100%;
    }
    .banner .image {
        margin-top: 30px;
    }
}
