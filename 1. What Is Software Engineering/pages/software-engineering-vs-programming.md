---
mdc: true
transition: slide-left
layout: default
---

<div class="text-teal-500 text-sm">
  MÓDULO 1: FUNDAMENTOS
</div>
<div class="text-sm">
  Ingeniería de Software vs Programación
</div>

<div class="grid cols-2 gap-7 my-7">
  <FoundationCard
    color="purple-500"
    title="Programación"
    description="Escribir código para resolver un problema específico y aislado. Se centra en la sintaxis, la lógica y su funcionamiento."
  >
    <mdi-code-block-tags class="text-purple-500" />
  </FoundationCard>

  <FoundationCard
    color="teal-500"
    title="Ingeniería De Software"
    description="Un enfoque sistemático para desarrollar, operar y mantener sistemas de software a escala a lo largo del tiempo."
  >
    <mdi-cog-outline class="text-teal-500" />
  </FoundationCard>
</div>

<table>
  <thead class="bg-slate-900 text-xs">
    <tr>
      <th class="px-4! text-slate-500">
        DIMENSIÓN
      </th>
      <th class="px-4! text-purple-500">
        ENFOQUE DE PROGRAMACIÓN
      </th>
      <th class="px-4! text-teal-500">
        ENFOQUE DE INGENIERÍA
      </th>
    </tr>
  </thead>
  <tbody class="text-xs">
    <tr class="bg-slate-800">
      <th class="flex items-center font-bold! px-4!">
        <div class="rounded bg-blue-500/10 p-1 flex justify-center items-center aspect-square mr-2">
          <mdi-scale-balance class="text-blue-500" />
        </div>
        Escala
      </th>
      <th class="text-slate-500 px-4!">
        Scripts, pequeñas aplicaciones, funciones individuales
      </th>
      <th class="px-4!">
        Grandes sistemas distribuidos, millones de usuarios
      </th>
    </tr>
    <tr class="bg-slate-800/50">
      <th class="flex items-center font-bold! px-4!">
        <div class="rounded bg-blue-500/10 p-1 flex justify-center items-center aspect-square mr-2">
          <mdi-user-group class="text-blue-500" />
        </div>
        Colaboración
      </th>
      <th class="text-slate-500 px-4!">
        A menudo en solitario o en grupos pequeños
      </th>
      <th class="px-4!">
        Equipos multifuncionales (PM, Diseño, Control de calidad, Operaciones)
      </th>
    </tr>
    <tr class="bg-slate-800">
      <th class="flex items-center font-bold! px-4!">
        <div class="rounded bg-blue-500/10 p-1 flex justify-center items-center aspect-square mr-2">
          <mdi-clock-time-five-outline class="text-blue-500" />
        </div>
        Horizonte Temporal
      </th>
      <th class="text-slate-500 px-4!">
        A corto plazo; "¿Funciona?"
      </th>
      <th class="px-4!">
        A largo plazo; mantenible durante años/décadas
      </th>
    </tr>
    <tr class="bg-slate-800/50">
      <th class="flex items-center font-bold! px-4!">
        <div class="rounded bg-blue-500/10 p-1 flex justify-center items-center aspect-square mr-2">
          <mdi-clipboard-check class="text-blue-500" />
        </div>
        Proceso
      </th>
      <th class="text-slate-500 px-4!">
        Ad hoc, informal
      </th>
      <th class="px-4!">
        Disciplinado (CI/CD, Revisión de código, Pruebas)
      </th>
    </tr>
  </tbody>
</table>
