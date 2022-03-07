<script>

</script>



<button id="navbarDropdown3" role="button" data-toggle="dropdown" aria-haspopup="true" class="standard-btn">
    Shopping cart
</button> 



<div class="dropdown-menu menu3" aria-labelledby="navbarDropdown3">
    <a class="dropdown-item">
        <div>
            <img src="./assets/images/meat.jpg" style="width: 40px;height: 40px"> Meat <input class="number-value" id="id_form-0-quantity" min="1" max="10" name="form-0-quantity" value="1" type="number"> <span class="dropdown-product-details">$10</span>
        </div>
    </a>
    <div class="dropdown-divider"></div>
    <a class="dropdown-item">
        <div>
            <img src="./assets/images/meat.jpg" style="width: 40px;height: 40px"> meat <input class="number-value" id="id_form-0-quantity" min="1" max="10" name="form-0-quantity" value="1" type="number"> <span class="dropdown-product-details">$10</span>
        </div>
    </a>
    <div class="dropdown-divider"></div>
    <a class="dropdown-item">
        <div>
            <img src="./assets/images/meat.jpg" style="width: 40px;height: 40px"> Meat <input class="number-value" id="id_form-0-quantity" min="1" max="10" name="form-0-quantity" value="1" type="number"> <span class="dropdown-product-details">$10</span>

            
        </div>
    </a>



    

    <div class="checkout">
            <button href="#"  class="custom-btn btn-16">Cheakout</button>
        </div>
    





</div>




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



.number-value{

    font-size: 13px;
    width: 30%;
    color:rgb(0, 0, 0);
    border-radius: 5px;
    border: solid 0.5px #000;
    background: #fff;
    



}



    
</style>