How To Create a Loader

  <div class="loader"></div>
  
    .loader {
    border: 16px solid #f3f3f3; /* Light grey */
    border-top: 16px solid #3498db; /* Blue */
    border-radius: 50%;
    width: 120px;
    height: 120px;
    animation: spin 2s linear infinite;
   

    @keyframes spin {
    0% { transform: rotate(0deg); }
    100% { transform: rotate(360deg); }
    }
    
    
<div class="parallax">xfhxhsdfg</div>

<div style="height:1000px;background-color:red;font-size:36px">
Scroll Up and Down this page to see the parallax scrolling effect.
This div is just here to enable scrolling.
Tip: Try to remove the background-attachment property to remove the scrolling effect.
</div>

<div class="parallax"></div>
    body, html {
    height: 100%;
}
.parallax {
    /* The image used */
    background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS9XidFccUPuDXNQ8hin-   sc38aGvujcQ6Gi3ZWqryqsD_st6SiNOg');
    /* Full height */
    height: 100%; 

    /* Create the parallax scrolling effect */
    background-attachment: fixed;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
}
