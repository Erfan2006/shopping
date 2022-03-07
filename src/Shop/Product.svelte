<script>


  import { navigate } from "svelte-routing";
  
  function navigateToMainpage(){
  
      navigate("/Mainpage"); 
  
      
  }
  
  </script>
    <div class="content">
      <img src="./assets/images/meat.jpg"/>
      <h3>Meat</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
      <h6>$100.00</h6>
      <button class="buy" on:click="{navigateToMainpage}">BUY</button>
    </div>
  
    
    
  
    
  
  
        <style>
  
  
  
        h3{
        text-align: center;
        font-size: 30px;
        margin: 0;
        padding-top: 10px;
        }
       
      
        .content{
        width: 24%;
        margin: 6px;
        box-sizing: border-box;
        float: left;
        text-align: center;
        border-radius:10px;
        border-top-right-radius: 10px;
        border-bottom-right-radius: 10px;
        padding-top: 10px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        transition: .4s;
        }
        .content:hover{
        box-shadow: 0 0 11px rgba(33,33,33,.2);
        transform: translate(0px, -8px);
        transition: .6s;
        }
        img{
        width: 200px;
        height: 200px;
        text-align: center;
        margin: 0 auto;
        display: block;
        }
        p{
        text-align: center;
        color: #b2bec3;
        padding: 0 8px;
        }
        h6{
        font-size: 26px;
        text-align: center;
        color: #222f3e;
        margin: 0;
        }
        
       
        button{
        text-align: center;
        font-size: 24px;
        color: #fff;
        width: 100%;
        padding: 15px;
        border:0px;
        outline: none;
        cursor: pointer;
        margin-top: 5px;
        border-bottom-right-radius: 10px;
        border-bottom-left-radius: 10px;
        }
        .buy{
        background-color: #2183a2;
        }
    
        @media(max-width: 1000px){
        .content{
        width: 46%;
        }
        }
        @media(max-width: 750px){
        .content{
        width: 46%;
        }
        }
  
  
  
        </style>