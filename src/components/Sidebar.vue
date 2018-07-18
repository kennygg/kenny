<template>
  <div class="sidebar">
   <div class="col-md-12 bootstrap-admin-col-left" style="background-color: #222d32;">
                    <ul class="nav navbar-collapse collapse bootstrap-admin-navbar-side">
                        <li>
                            <a href="#"> About</a>
                        </li>                       
                    </ul>
                </div>
  </div>
  
</template>
 
<script>
export default {
  name: 'Sidebar'   
}
</script>
<style>
  .sidebar{
     height:auto;
position: fixed;
    top: 0;
    bottom: 0;    
    padding-top: 70px;
    width: 230px;
    overflow: auto;    
    background-color: #222d32;
    -webkit-box-shadow: 0px 8px 17px rgba(0, 0, 0, 0.2);
    box-shadow: 0px 8px 17px rgba(0, 0, 0, 0.2);
    -webkit-transition: left 0.3s ease,
 width 0.3s ease;
    -o-transition: left 0.3s ease,
 width 0.3s ease;
    transition: left 0.3s ease,
 width 0.3s ease;
   color:white,

  }
</style>