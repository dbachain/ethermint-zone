<template lang="pug">
.page-index
  section-cover
  section-benefits
</template>

<script>
import SectionCover from 'sections/SectionCover'
import SectionBenefits from 'sections/SectionBenefits'
export default {
  name: 'page-index',
  components: {
    SectionCover,
    SectionBenefits
  },
  head: {
    title () {
      return {
        inner: 'Cosmos',
        separator: '-',
        complement: 'Internet of Blockchains'
      }
    }
  }
}
</script>
