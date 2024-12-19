<script setup lang="ts">
import { useBrowserLamion } from "@lamion-libs/impl";

const { logEvent } = useBrowserLamion({
  accessKey: "vuOMCfHq5pIE8hm3A5Ia",
});
</script>

<template>
  <div>
    <button @click="logEvent('login', 'Authorization')">Make login!</button>
    <button @click="logEvent('registartion', 'Authorization')">Make registration!</button>
    <button @click="logEvent('login', 'posts')">Make posts like!</button>
    <button @click="logEvent('create comment', 'comments')">create comment!</button>
    <button @click="logEvent('go out of home', 'activity')">go out of home!</button>
    <button @click="logEvent('play with a friends', 'activity')">play with a friends!</button>
    <button @click="logEvent('input text', 'meta')">input text</button>
  </div>
</template>
