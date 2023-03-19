<template>
    <main>
      <div class="bg-gray-300">
            <div class="container mx-auto h-10 flex-items-center">
              <div class="flex">
                <nav>
                
                  Menu
            
                </nav>

                <div class="flex-initial mx-auto flex-items-center">
                         <nav class="self-center flex-items-center">
                        <NuxtLink to="/home" >Home</NuxtLink> 
                        </nav>
                </div>
                <div class="flex-initial mx-auto flex-items-center">
                         <nav class="self-center flex-items-center"><NuxtLink to="/About">
                            About
                        </NuxtLink></nav>
                </div>
                <div class="flex-initial w-32 ...">
                  <NuxtLink to="/Service" >Service</NuxtLink> 
                </div>
              </div>
                
            </div>
            
          </div>
        
        <div class="container mx-auto">
       <h2 class="text-lg font-bold">Home-Segunda pagina</h2>
       <p class="flex justify">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras dignissim erat velit, at dignissim enim dictum a. Fusce nec luctus leo. Morbi malesuada velit ligula, in congue turpis tincidunt eu. Ut tempor, ante at euismod consectetur, felis sem vestibulum ipsum, vitae condimentum massa dui et tellus. Donec eleifend, felis nec elementum volutpat, massa diam vehicula ligula, vitae ultrices dolor augue at arcu. Phasellus cursus velit enim, rutrum volutpat tellus mattis ut. Sed congue lectus sit amet est placerat vestibulum. Aliquam erat volutpat. Nulla facilisi. Vivamus vulputate vehicula diam at consectetur. Quisque velit justo, pretium pellentesque fermentum eu, efficitur id metus. Aenean massa orci, pretium ut diam sit amet, aliquam mattis libero.

       </p>
       
       <NuxtLink to="/About">
       <button class="bg-blue-500 hover:bg-blue-400 text-white font-bold py-2 px-4 border-b-4 border-blue-700 hover:border-blue-500 rounded">
         Avançar
        </button>
       </NuxtLink>
        <NuxtLink to="/">
            <button class="bg-red-500 hover:bg-red-700 text-white font-bold py-2 px-4 rounded">
                Voltar
            </button>
        </NuxtLink>
    
    
    
      </div>
    
    
</main>
</template>
  
  <script>
  export default {
    name: '',
    data(){
      return{
  
      };
    },
    methods:{},
  };
  </script>
  