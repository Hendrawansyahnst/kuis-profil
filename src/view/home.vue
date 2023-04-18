<template>

    <section id = "sec-2" class = "py-5">
      <div class = "container my-4">
        <div class = "row gx-lg-5">
          <div class = "col-lg-6 mb-5">
            <img src = "../assets/IMG-20200928-WA0060.jpg" class = "img-fluid" height="600px" width="900px">
          </div>
          <div class = "col-lg-6">
            <h3>About me</h3>
            <p class = "text-muted fw-light lh-lg my-4"> Hello Gais </p>
            <p class = "text-muted fw-light lh-lg my-4"> Nama saya Hendrawansyah Nasution, saya lahir pada tanggal Agustus 2001 di kota Pekanbaru, sekarang saya tinggal di Pekanbaru. dan profesi saya adalah mahasiswa di UIN Sultan Syarif Kasim Riau dan membuat usaha jasa design dengan ini saya ingin memperkenalkan usaha saya dan teman saya kepada bapak/ibu/teman-teman yang liat web profile ini.</p>
            <p class="text-muted fw-light lh-lg my-4"> TERIMAKASIH </p>
          </div>
        </div>
      </div>
    </section>
  
    
  </template>
  
  <script>
  export default {
    name: 'App',
    components: {
    }
  }
  </script>
  
  <style>
  :root{
    --blue: #4B65E8F4;
    --blue-dark: #444BCCF4;
    --light-grey: #f1f4f6;
  }
  
  *{
    font-family: 'Roboto', sans-serif;
  }
  .col-lg-6{
    font-size: 20px;
    margin-top: -700px;
  }
  
  ul li{
    list-style-type: none;
  }
  .container{
    max-width: 1200px;
  }
  .display-1{
    letter-spacing: 1px;
  }
  .bg-blue{
    background-color: var(--blue)!important;
  }
  .bg-grey{
    background-color: var(--light-grey);
  }
  .text-blue{
    color: var(--blue);
  }
  .lh-lg{
    line-height: 2.7!important;
  }

  </style>