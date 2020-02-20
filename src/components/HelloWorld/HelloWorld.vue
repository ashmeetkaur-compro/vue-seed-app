<template src="./HelloWorld.html"></template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class HelloWorld extends Vue {
  @Prop() private msg!: string;
}
</script>

<style lang="scss" src="./HelloWorld.scss" scoped></style>
