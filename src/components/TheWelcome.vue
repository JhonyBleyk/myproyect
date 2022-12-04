<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import Fontawensome from './icons/fontawensome.vue'

</script>

<template>
  

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Stetic News</template>
    <input type="search"  placeholder="Buscar" list="lista" />
    
    <td> <h2>Cooperaciones </h2> </td>
    <td> Argentina</td>
    <p class="template"  maxlength="6" /> 
    <td>"Nueva adquisición: SteticABC acaba de anunciar un acuerdo para
    comprar SteticDEF con el objetivo de aumentar su presencia en el mercado alemán. El
    acuerdo se estima en alrededor de 2 millones de euros Lea más en: 
    <a href="https://SteticNews.com" target="_blank" rel="noopener">SteticNews</a> o
    <a href="https://NewsDaily.com" target="_blank" rel="noopener">NewsDaily</a>”.</td>
    
    <a>const fecha = new Date('Jul 12 2011');</a>


    <br /><br />
    <div id="app">
  <h2>Contador de 
  <br> Caracteres: </h2>
  <input class="input"  maxlength="255"/> 
     <div v-html="miHtml" ></div>
</div>    
    <br />    
    
    <br />
       
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Stetic News</template>
        
    <td> <h2>Lanzamientos de productos </h2> </td>
    <td> Portugal</td>
    <p class="template"  maxlength="6" /> 
    <td>Nueva adquisición: SteticABC acaba de anunciar un acuerdo para comprar SteticDEF 
      con el objetivo de aumentar su presencia en el mercado Alemán. El acuerdo se estima 
      en alrededor de 2 millones de euros. Lea más en 
    <a href="https://SteticNews.com" target="_blank" rel="noopener">SteticNews</a> o
    <a href="https://NewsDaily.com" target="_blank" rel="noopener">NewsDaily</a>”.</td>
    
      <br />
      
      <imput> const fecha = new Date();</imput> 

  </WelcomeItem>
  
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Stetic News</template>
        
    <td> <h2>Lanzamientos de productos </h2> </td>
    <td> Portugal</td>
    <p class="template"  maxlength="6" /> 
    <td>Nueva adquisición: SteticABC acaba de anunciar un acuerdo para comprar SteticDEF 
      con el objetivo de aumentar su presencia en el mercado Alemán. El acuerdo se estima 
      en alrededor de 2 millones de euros. Lea más en 
    <a href="https://SteticNews.com" target="_blank" rel="noopener">SteticNews</a> o
    <a href="https://NewsDaily.com" target="_blank" rel="noopener">NewsDaily</a>”.</td>
    
      <br />
      <span>const fecha = new Date('Dic 02 2022');</span>
      <br />
     
    
  </WelcomeItem>
  
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Stetic News</template>
    
    <td>
    <td> <h2>Compras y adquisiciones </h2> </td>
    <td> Italia</td></td> 
    <p class="template"  maxlength="6" /> 
    <td>La empresa Almalaser ha finalizado operaciones en Argentina, no ha podido continuar con sus 
      labores dado que el mercado ha cambiado y no pudo competir con la tecnología que estan usando 
      hoy en día los equipos, quedando atrás en el mercado.
    <a href="https://SteticNews.com" target="_blank" rel="noopener">SteticNews</a> o
    <a href="https://NewsDaily.com" target="_blank" rel="noopener">NewsDaily</a>”.</td>
    
      <br />
      <a>const fecha = new Date('Dic 02 2022');</a>
       
      
  </WelcomeItem>

  
<template>
  <h1>ultimo agregado</h1>
  <template v-for="branch in branches">
    <input type="radio"
      :id="branch"
      :value="branch"
      name="branch"
      v-model="currentBranch">
    <label :for="branch">{{ branch }}</label>
  </template>
  <p>vuejs/vue@{{ currentBranch }}</p>
  <ul>
    <li v-for="{ html_url, sha, author, commit } in commits">
      <a :href="html_url" target="_blank" class="commit">{{ sha.slice(0, 7) }}</a>
      - <span class="message">{{ truncate(commit.message) }}</span><br>
      by <span class="author">
        <a :href="author.html_url" target="_blank">{{ commit.author.name }}</a>
      </span>
      at <span class="date">{{ formatDate(commit.author.date) }}</span>
    </li>
  </ul>
</template>


 
</template>
