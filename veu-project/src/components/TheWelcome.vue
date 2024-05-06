<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>ABOUT ME</template>

   hello this is me studying cybersecurity,software engineering and data science
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>E
    
    </template>
    <template #heading>EDUCATION</template>
    <br>
   Secondary certifcate
   <br>
   primary certificate
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>SKILLS</template>
average
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>HOBBIES</template>
playing football
<br>
watching movies
<br>
listening to music
<br>
playing volleyball


    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>CONTACT INFO</template>
EMAIL:mambeacollins@gmail.Com
<br>
TEL:0759981302

   
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener"></a>.
  </WelcomeItem>
</template>
