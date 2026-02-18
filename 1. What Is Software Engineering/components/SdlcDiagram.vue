<script setup lang="ts">
</script>

<template>
  <div class="relative w-full h-[450px] flex items-center justify-center scale-75 origin-top mt-16">
    <div class="absolute z-10 text-center flex flex-col items-center justify-center w-60 h-60 bg-slate-900 rounded-full border-4 border-slate-800 shadow-xl">
      <div class="text-xl font-bold text-white mb-1">
        Valor<br>Continuo
      </div>
      <div class="text-xs text-slate-400 px-2">
        El software nunca está "terminado", solo evoluciona.
      </div>
    </div>

    <div class="absolute w-[350px] h-[350px] rounded-full border-2 border-dashed border-slate-700/50"></div>

    <div class="absolute top-0 left-1/2 -translate-x-1/2 -translate-y-1/2 w-48">
      <div class="bg-slate-900 border border-slate-700 rounded-xl p-3 shadow-lg relative z-20">
        <div class="absolute -top-5 left-1/2 -translate-x-1/2 bg-yellow-500 flex items-center justify-center px-2 aspect-square rounded-full">
          <mdi-lightbulb-on-outline />
        </div>
        <div class="mt-3 text-center">
          <div class="font-bold text-white">Idea</div>
          <div class="text-[10px] text-slate-400 leading-tight mt-1">Identificar problema, oportunidad y valor</div>
        </div>
      </div>
    </div>

    <div class="absolute top-[12%] right-[10%] w-48">
      <div class="bg-slate-900 border border-slate-700 rounded-xl p-3 shadow-lg relative z-20">
        <div class="absolute -top-5 left-1/2 -translate-x-1/2 bg-purple-500 px-2 flex items-center justify-center aspect-square rounded-full">
           <mdi-clipboard-text-outline />
        </div>
        <div class="mt-3 text-center">
          <div class="font-bold text-white">Planificación</div>
          <div class="text-[10px] text-slate-400 leading-tight mt-1">Alcance, roadmap, riesgos y recursos</div>
        </div>
      </div>
    </div>

    <div class="absolute top-[51%] right-[8%] -translate-y-1/2 w-48">
      <div class="bg-slate-900 border border-slate-700 rounded-xl p-3 shadow-lg relative z-20">
        <div class="absolute -top-5 left-1/2 -translate-x-1/2 bg-pink-500 px-2 rounded-full aspect-square flex items-center justify-center">
          <mdi-pencil-ruler />
        </div>
        <div class="mt-3 text-center">
          <div class="font-bold text-white">Diseño</div>
          <div class="text-[10px] text-slate-400 leading-tight mt-1">Arquitectura, flujos UX y modelos de datos</div>
        </div>
      </div>
    </div>

    <div class="absolute bottom-[11%] right-[12%] w-48">
      <div class="bg-slate-900 border border-slate-700 rounded-xl p-3 shadow-lg relative z-20">
        <div class="absolute -top-5 left-1/2 -translate-x-1/2 bg-blue-500 px-2 rounded-full aspect-square flex items-center justify-center">
          <mdi-code-tags />
        </div>
        <div class="mt-3 text-center">
          <div class="font-bold text-white">Código</div>
          <div class="text-[10px] text-slate-400 leading-tight mt-1">Implementación y revisión por pares</div>
        </div>
      </div>
    </div>

    <div class="absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-1/2 w-48">
      <div class="bg-slate-900 border border-slate-700 rounded-xl p-3 shadow-lg relative z-20">
        <div class="absolute -top-5 left-1/2 -translate-x-1/2 bg-green-500 px-2 rounded-full aspect-square flex items-center justify-center">
          <mdi-bug-outline />
        </div>
        <div class="mt-3 text-center">
          <div class="font-bold text-white">Pruebas</div>
          <div class="text-[10px] text-slate-400 leading-tight mt-1">Validar calidad, seguridad y corrección</div>
        </div>
      </div>
    </div>

    <div class="absolute bottom-[8%] left-[12%] w-48">
      <div class="bg-slate-900 border border-slate-700 rounded-xl p-3 shadow-lg relative z-20">
        <div class="absolute -top-5 left-1/2 -translate-x-1/2 bg-red-500 px-2 rounded-full aspect-square flex items-center justify-center">
          <mdi-rocket-launch />
        </div>
        <div class="mt-3 text-center">
          <div class="font-bold text-white">Despliegue</div>
          <div class="text-[10px] text-slate-400 leading-tight mt-1">Enviar a producción de forma segura</div>
        </div>
      </div>
    </div>

     <div class="absolute top-1/2 left-[8%] -translate-y-1/2 w-48">
      <div class="bg-slate-900 border border-slate-700 rounded-xl p-3 shadow-lg relative z-20">
        <div class="absolute -top-5 left-1/2 -translate-x-1/2 bg-teal-500 px-2 rounded-full aspect-square flex items-center justify-center">
          <mdi-heart-pulse />
        </div>
        <div class="mt-3 text-center">
          <div class="font-bold text-white">Mantener</div>
          <div class="text-[10px] text-slate-400 leading-tight mt-1">Monitorear, arreglar bugs y apoyar usuarios</div>
        </div>
      </div>
    </div>

    <div class="absolute top-[12%] left-[11%] w-48">
      <div class="bg-slate-900 border border-slate-700 rounded-xl p-3 shadow-lg relative z-20">
        <div class="absolute -top-5 left-1/2 -translate-x-1/2 bg-indigo-500 px-2 rounded-full aspect-square flex items-center justify-center">
          <mdi-refresh />
        </div>
        <div class="mt-3 text-center">
          <div class="font-bold text-white">Iterar</div>
          <div class="text-[10px] text-slate-400 leading-tight mt-1">Aprender de los datos y mejorar</div>
        </div>
      </div>
    </div>
  </div>
</template>
