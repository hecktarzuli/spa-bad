<template>
  <div></div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Social Sharing Test',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: "This is a description"
        },
        { hid: 'og-type', property: 'og:type', content: 'website' },
        { hid: 'og-title', property: 'og:title', content: "Social Share Test" },
        { hid: 'og-image', property: 'og:image', content: "https://images.unsplash.com/photo-1518331647614-7a1f04cd34cf?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=2249&q=80" },
        { hid: 'og-url', property: 'og:url', content: "https://blarg.net" },
        {
          hid: 'og-desc',
          property: 'og:description',
          content: "This is a description"
        },
        { hid: 't-type', name: 'twitter:card', content: 'summary_large_image' },
        { hid: 't-site', name: 'twitter:site', content: '@joshdeltener' }
      ]
    }
  },
}
</script>