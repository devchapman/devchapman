CRM Landing (header)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous">
</head>
<style>
    .headimage {position: relative;
                top: -375px;  
                right: 140px;
                display: flex;
                flex-direction: row;
                justify-content: end;
                margin: 0 120px 60px 0;}
    
     .grid-container {margin: 20px 0 0 150px; 
                    position: relative;
                    top: 30px;}

    .headline {font-size: xxx-large;}
                      

    .handle {font-size: 20px;}

    #fade {font-size: 15px;
            font-weight: 100;
            color: grey;
        position: relative;
        max-width: 300px;
        min-width: 400px;}
       
        

    .btn-primary {background-color: rgb(0, 0, 150); border: rgb(0, 0, 150);height: -10px;}

    .bi-chevron-right {color: white; position: relative; left: 30px; size: 8px;}

  .btn-light {margin-left: 30px;}

 .bi-chat-dots-fill {color: rgb(0, 0, 150);}

 .doubletap {color: grey; font-size: 20px; font-weight: 100;position: relative;top: 20px;}

 .line {width: 50%;
        margin-left: auto;
        margin-right: auto;
        position: relative;
        bottom: 350px;}

.space {display: flex;;
        margin-top: 50px;}

p{font-size: 10px;}

.cancel {position: relative;
        left: 50px;
        right: 45px;}

.bi-circle-fill {position: relative;
                top: 4px;}

.circle1 {position: relative;
            left: 10px;
            bottom: 10px;
            color: rgb(0, 0, 150)}

.circle2 {position: relative;              
            bottom: 10px;
               left: 30px;
               color: rgb(0, 0, 150) }

.manage {position: relative;
        left: 20px;}



</style>


<body>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>
  
<header>
    <div class="grid-container"> 
    <h1 class="headline">Focus on</h1>
    <h1 class="headline">Your Business</h1>
    <p class="handle"><b>Let Us Handle Everything Else</b></p>
    <p id="fade"><b>Subscription Billing, powered with revenue retention tools and a seamless customer experience - without the technical hurdles.</b></p>
   
    <div class="buttons">
    <button type="button" class="btn btn-primary">
            <span class="button--text">Sign Up Free</span>
                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-chevron-right" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z"/>
                  </svg>
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-chevron-right2" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M4.646 1.646a.5.5 0 0 1 .708 0l6 6a.5.5 0 0 1 0 .708l-6 6a.5.5 0 0 1-.708-.708L10.293 8 4.646 2.354a.5.5 0 0 1 0-.708z"/>
                  </svg>
        </button>

        <button type="button" class="btn btn-light">
            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-chat-dots-fill" viewBox="0 0 16 16">
                <path d="M16 8c0 3.866-3.582 7-8 7a9.06 9.06 0 0 1-2.347-.306c-.584.296-1.925.864-4.181 1.234-.2.032-.352-.176-.273-.362.354-.836.674-1.95.77-2.966C.744 11.37 0 9.76 0 8c0-3.866 3.582-7 8-7s8 3.134 8 7zM5 8a1 1 0 1 0-2 0 1 1 0 0 0 2 0zm4 0a1 1 0 1 0-2 0 1 1 0 0 0 2 0zm3 1a1 1 0 1 0 0-2 1 1 0 0 0 0 2z"/>
              </svg>
              <span class="button--text">Chat With Us</span>

        </button>
     <p class="doubletap">Already using <b>Double</b>Tap? <b>Sign In</b></p>  
     
    <div class="space"> 
        <p>Free 14 day trial</p>
      <div class="circle1"><svg xmlns="http://www.w3.org/2000/svg" width="5" height="10" fill="currentColor" class="bi bi-circle-fill" viewBox="0 0 16 16">
            <circle cx="8" cy="8" r="8"/>
          </svg></div> 
         <div class="manage"><p>Manage Customers In Minutes</p></div>
         <div class="circle2"><svg xmlns="http://www.w3.org/2000/svg" width="5" height="10" fill="currentColor" class="bi bi-circle-fill" viewBox="0 0 16 16">
            <circle cx="8" cy="8" r="8"/>
          </svg></div>
       <div class="cancel"><p>Cancel at Anytime</p></div> 
    </div>
    
    </div>

</div>



    <div class="headimage"><img src="./images/Header-Side.png" alt="Header-Side" height="500" width="400"></div>

    <hr class="line">



</header>
