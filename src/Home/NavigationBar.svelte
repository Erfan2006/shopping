
<head>
    <title>Matir Dokan</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/css/bootstrap.min.css" integrity="sha384-9gVQ4dYFwwWSjIDZnLEWnxCjeSWFphJiwGPXr1jddIhOegiu1FwO5qRGvFXOdJZ4" crossorigin="anonymous">

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.0/umd/popper.min.js" integrity="sha384-cs/chFZiN24E4KMATLdqdvsezGxaGsi4hLGOzlXwp5UZB1LY//20VyM2taTB4QvJ" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.0/js/bootstrap.min.js" integrity="sha384-uefMccjFJAIv6A+rW+L4AHf99KvxDjWSu1z9VI8SKNVmz4sk7buKt/6v9KI65qnm" crossorigin="anonymous"></script>
    <link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
    
</head>

<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Matir Dokan</a>

    
    <!-- Dropdown shopping cart  -->

    
        <button id="navbarDropdown3" role="button" data-toggle="dropdown" aria-haspopup="true" class="standard-btn">
            Shopping cart
        </button>

        
        
        <div class="dropdown-menu menu3" aria-labelledby="navbarDropdown3">
            <a class="dropdown-item">
                <div>
                    <img src="./assets/images/meat.jpg" style="width: 40px;height: 40px"> Meat  <span class="dropdown-product-details">2 x $24.89</span>
                </div>
            </a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item">
                <div>
                    <img src="./assets/images/meat.jpg" style="width: 40px;height: 40px"> meat <span class="dropdown-product-details">2 x $24.89</span>
                </div>
            </a>
            <div class="dropdown-divider"></div>
            <a class="dropdown-item">
                <div>
                    <img src="./assets/images/meat.jpg" style="width: 40px;height: 40px"> Meat <span class="dropdown-product-details">2 x $24.89</span>
                </div>
            </a>


            <div class="checkout">
                    <button href="#" class="custom-btn btn-16">Cheakout</button>
                </div>
            





        </div>
  


    <!-- end -->



    
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
            <li class="nav-item active">
                <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            
            <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
            </li>



            <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
            </li>




            <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
            </li>




            <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
            </li>







            
            </ul>
            </div>
            </nav>







        

<style>
    
    .navbar {
        margin-bottom: 10px;
        border-radius: 0;
    }

    .standard-btn{

    border: none;
    background-color: inherit;
    font-size: 16px;
    cursor: pointer;
    display: inline-block;


    }


    .standard-btn {color: red;}




  /* 16 */
.btn-16 {
  width: 200px;
  border: none;
  color: #000;
 
}
.btn-16:after {
  position: absolute;
  content: "";
  width: 0;
  height: 100%;
  top: 0;
  left: 0;
  direction: rtl;
  z-index: -1;
  box-shadow:
   -7px -7px 20px 0px #fff9,
   -4px -4px 5px 0px #fff9,
   7px 7px 20px 0px #0002,
   4px 4px 5px 0px #0001;
  transition: all 0.3s ease;
}
.btn-16:hover {
  color: rgba(0, 0, 0, 0.6);
}
.btn-16:hover:after {
  left: auto;

}
.btn-16:active {
  top: 2px;
}


.checkout{
    float: center;
    padding: 20px;
    align-items: center;
}



</style>