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
        inner: 'Ethermint',
        separator: '-',
        complement: 'Cosmos Zone'
      }
    }
  }
}
</script>
