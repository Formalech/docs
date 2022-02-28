*{
   margin: 0;
   padding: 0;
   box-sizing: border-box;
}
body{
   background: url(https://images.pexels.com/photos/3184454/pexels-photo-3184454.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500);
   background-size:cover;
   font-family: sans-serif;
   
}
.menu-bar{
   background: rgb(7, 151, 38);
   text-align: center;  
}
.menu-bar ul{
   display: inline-flex;
   list-style: none;
  
}
.menu-bar ul li
{
   width:120px;
   margin: 15px;
   padding: 10px;
   
}
.menu-bar ul li a{
   text-decoration: none;
   color:white;
   font-family: Georgia; 
}
ul li a:hover{
   color: rgb(133, 8, 101);
}
.menu-bar .fa-solid{
   margin-right: 10px;
}




.submenuA{
   display: none;
}
.menu-bar ul li:hover .submenuA{
   display: block;
   position: absolute;
   background-color:rgb(7, 151, 38);
   border-radius: 15px 10px 60px;
}
.menu-bar ul li:hover .submenuA ul
{
   display: block;
}
.menu-bar ul li:hover .submenuA ul li
{
   width: 150px;
   padding: 10px;
   border-bottom: 1px dashed white;
   text-align: left;
}
.menu-bar ul li:hover .submenuA ul li:last-child
{
   border-bottom: none;
}
.menu-bar ul li:hover .submenuA ul li a:hover
{
   color:yellow;
}


<!..footer...> 

