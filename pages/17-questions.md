---
layout: center
class: text-center
---

# Les Autres Domaines du Développement Web

<div class="flex flex-wrap justify-center gap-4">
<v-clicks>
<div class="framework-bubble">
  <img src="/logos/nginx.svg" alt="Nginx Icon" class="icon" />
  <h3 class="text-lg font-bold">Nginx</h3>
  <div class="bubble-content">
    <p class="text-sm">Comment avoir un serveur web résiliant ?</p>
  </div>
</div>

<div class="framework-bubble">
  <img src="/logos/dns.svg" alt="DNS Icon" class="icon" />
  <h3 class="text-lg font-bold">DNS</h3>
  <div class="bubble-content">
    <p class="text-sm">Comment configurer un DNS ?</p>
  </div>
</div>

<div class="framework-bubble">
  <img src="/logos/docker.svg" alt="Déploiement Moderne Icon" class="icon" />
  <h3 class="text-lg font-bold">Déploiement Moderne</h3>
  <div class="bubble-content">
    <p class="text-sm">Avec Docker / Kubernetes : avantages et défis ?</p>
  </div>
</div>

<div class="framework-bubble">
  <img src="/logos/aws.svg" alt="Cloud Providers Icon" class="icon" />
  <h3 class="text-lg font-bold">Cloud Providers</h3>
  <div class="bubble-content">
    <p class="text-sm">Quid de AWS, Azure Cloud, Heroku, Vercel ... ?</p>
  </div>
</div>

</v-clicks>
</div>

<style>
.framework-bubble {
  @apply bg-white rounded-xl p-4 shadow-md text-center w-48 transition-transform hover:scale-105;
}

.bubble-content {
  @apply mt-2 space-y-2;
}

.icon {
  @apply w-12 h-12 mx-auto mb-2;
}
</style>