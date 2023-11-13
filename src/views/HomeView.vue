<script setup lang="ts">
</script>

<template>
  <main class="antialiased bg-gray-900 text-white text-sm flex flex-col w-screen min-h-screen">
    <div class="w-full mx-auto max-w-2xl mt-5 px-8">
      <header class="flex justify-end items-center">
        <div class="flex justify-center items-center bg-gray-950 rounded-full py-1 px-3 md:py-2 md:px-4 gap-1 cursor-pointer transition-all hover:scale-105">
          <ph-instagram-logo :size="20" class="text-fuchsia-700" />
          <a href="https://www.instagram.com/eu.caiquealves/" target="_blank" class="font-bold">@eu.caiquealves</a>
        </div>
      </header>
      <section class="mt-5 md:mt-8 flex flex-col justify-center items-center gap-3 md:gap-5">
        <img class="w-28 h-28 md:w-40 md:h-40 rounded-full" src="../assets/perfil_caique.jpeg" alt="Perfil">
        <h1 class="text-lg md:text-2xl">Caique Alves</h1>
        <p class="text-center md:text-base">Gestor de tráfego para empresas e infoprodutores. Agende uma reunião para discutir como posso impulsionar o seu crescimento.</p>
        <a 
          href="https://api.whatsapp.com/send?phone=75999948850&text=Ol%C3%A1%2C+vim+pela+bio+do+seu+instagram+e+quero+um+or%C3%A7amento+de+tr%C3%A1fego+para+meu+neg%C3%B3cio"
          target="_blank"
          class="relative cursor-pointer flex justify-center items-center w-full border-2 rounded mt-4 md:mt-6 p-3 transition-all hover:scale-105"
        >
          <ph-whatsapp-logo class="absolute left-2 top-[6px] text-green-700" :size="32" />
          <span class="md:text-base text-green-700">Orçamento Tráfego Pago</span>
        </a>
        <div class="flex flex-col justify-center items-center mt-6 gap-4">
          <h2 class="text-lg tracking-wider">Sobre mim</h2>
          <p class="text-center md:text-base">Gestor de tráfego com mais de 2 anos de experiência, liderando estratégias para mais de 10 empresas. Em busca de novos parceiros de negócio para impulsionar o crescimento. Colaborei com redes de estética de renome, como Botopremium e Botoclinic. Especializado em otimização de campanhas e análise de dados, comprometido em oferecer resultados excepcionais e prontos para enfrentar novos desafios.</p>
        </div>
      </section>
      <footer class="flex justify-between w-3/5 md:w-4/5 items-center my-10 mx-auto text-3xl md:text-4xl">
        <ph-rocket-launch class="text-violet-600" />
        <ph-whatsapp-logo class="text-green-700" />
        <ph-facebook-logo class="text-blue-700" />
        <ph-messenger-logo class="text-blue-200" />
        <ph-instagram-logo class="text-fuchsia-700" />
        <ph-google-drive-logo class="text-amber-300" />
      </footer>
    </div>
  </main>
</template>
