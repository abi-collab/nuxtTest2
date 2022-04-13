<template lang="pug">
  #header
    header.header
      nav.navbar.navbar-expand-lg.fixed-top.py-3
        .container
        a.navbar-brand.text-uppercase.font-weight-bold(href='#') Transparent Nav
        button.navbar-toggler.navbar-toggler-right(type='button' data-toggle='collapse' data-target='#navbarSupportedContent' aria-controls='navbarSupportedContent' aria-expanded='false' aria-label='Toggle navigation')
          i.fa.fa-bars
        #navbarSupportedContent.collapse.navbar-collapse
            ul.navbar-nav.ml-auto
            li.nav-item.active
              a.nav-link.text-uppercase.font-weight-bold(href='#')
                | Home 
              span.sr-only (current)
            li.nav-item
              a.nav-link.text-uppercase.font-weight-bold(href='#') About
            li.nav-item
              a.nav-link.text-uppercase.font-weight-bold(href='#') Gallery
            li.nav-item
              a.nav-link.text-uppercase.font-weight-bold(href='#') Portfolio
            li.nav-item
              a.nav-link.text-uppercase.font-weight-bold(href='#') Contact
</template>
<script>
export default {
    setup() {
        
    },
}
</script>