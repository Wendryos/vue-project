 
 
  <template>
     <div class="home">
      <h1> Primeira lista de sopas </h1>
         <ul>
            <li> <img src="@/assets/soup.webp">    Sopa de Carneiro </li>
            <li> <img src="@/assets/frango.webp">  Sopa de Frango   </li>
            <li> <img src="@/assets/carne.webp">   Sopa de Carne    </li>
        </ul>
    </div>
  </template>
  


   <style>

 h1 {
  color: #000;
  font-weight: 1000;
  text-align: center;
  margin-bottom: 15px;
 }


   li {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
    color: #000;
    font-weight: 800;
    width: 100%;
   }

  img {
    width: 96px;
    height: auto;
    object-fit: contain;
    margin-right: 10px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0,0,0,0.5);
  }

  </style>
  