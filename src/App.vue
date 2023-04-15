<script setup>
import Button from './components/base/Button.vue'
</script>


<template>
	<h1 className="text-3xl text-red-200 font-bold underline">
		Hello world!
	</h1>

	<Button class="bg-red-200" :icon="'icon_agora_icon'">Click</Button>
	<Button class="bg-red-200" >Click 2</Button>
</template>