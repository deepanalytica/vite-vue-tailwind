<template>
  <header class="navbar bg-base-100">
    <div class="flex-none">
      <a class="btn btn-ghost text-xl normal-case">Deep Analytica</a>
    </div>
    <div class="flex-none">
      <ul class="menu menu-horizontal p-0">
        <li>
          <router-link to="/">Inicio</router-link>
        </li>
        <li>
          <router-link to="/not-found">Servicios</router-link>
        </li>
        <li>
          <router-link to="/about">Nosotros</router-link>
        </li>
      </ul>
    </div>
    <div class="flex-1">
      <slot></slot>
    </div>
  </header>
</template>

<script setup lang="ts">
import { useCounterStore } from '@/stores/counter'

const counter = useCounterStore()
</script>
