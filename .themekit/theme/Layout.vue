<script setup>
import DefaultTheme, { VPHomeHero } from 'themekit-js/theme'
import { useData } from 'themekit-js'    
const { site, frontmatter,localeIndex } = useData()
const { Layout } = DefaultTheme
</script> 
<template> 
  <Layout>
      <template #sidebar-nav-after ></template>  
      <template #aside-bottom></template>
  </Layout> 
</template> 
<style scoped>  
   
</style>