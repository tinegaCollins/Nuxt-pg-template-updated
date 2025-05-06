<template>
  <UApp>
    <NuxtRouteAnnouncer />
    <NuxtPage />
    <Notivue v-slot="item">
      <Notification :item="item" />
    </Notivue>
  </UApp>
</template>
