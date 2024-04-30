<template>
  <div class="stats2-container thq-section-padding"
    ><div class="stats2-max-width thq-section-max-width"
      ><div class="thq-flex-column"
        ><img
          :alt="image1Alt"
          :src="image1Src"
          class="thq-img-ratio-1-1 stats2-image" /></div
      ><div class="stats2-container2 thq-flex-column"
        ><span class="thq-body-small">{{ content1 }}</span
        ><h2 class="thq-heading-2">{{ heading1 }}</h2
        ><p class="thq-body-large">{{ content2 }}</p
        ><div class="stats2-container3 thq-grid-2"
          ><div class="stats2-container4"
            ><h2 class="thq-heading-2">{{ stat1 }}</h2
            ><span class="thq-body-small">{{ stat1Description }}</span></div
          ><div class="stats2-container5"
            ><h2 class="thq-heading-2">{{ stat2 }}</h2
            ><span class="thq-body-small">{{ stat2Description }}</span></div
          ></div
        ><div class="stats2-container6 thq-grid-2"
          ><div class="stats2-container7"
            ><h2 class="thq-heading-2">{{ stat3 }}</h2
            ><span class="thq-body-small">{{ stat3Description }}</span></div
          ><div class="stats2-container8"
            ><h2 class="thq-heading-2">{{ stat4 }}</h2
            ><span class="thq-body-small">{{ stat4Description }}</span></div
          ></div
        ></div
      ></div
    ></div
  >
</template>

<script>
export default {
  name: 'Stats2',
  props: {
    stat2: {
      type: String,
      default: '90%',
    },
    stat1Description: {
      type: String,
      default: 'consectetur adipiscing elit,',
    },
    stat3Description: {
      type: String,
      default: 'consectetur adipiscing elit,',
    },
    stat2Description: {
      type: String,
      default: 'consectetur adipiscing.',
    },
    heading1: {
      type: String,
      default: 'Customer results presented in a fashion way',
    },
    content2: {
      type: String,
      default:
        'Business improvements emphasized with numbers to increase creadibility',
    },
    image1Src: {
      type: String,
      default: 'https://play.teleporthq.io/static/svg/default-img.svg',
    },
    stat1: {
      type: String,
      default: '80%',
    },
    stat4: {
      type: String,
      default: '100%',
    },
    stat3: {
      type: String,
      default: '95%',
    },
    image1Alt: {
      type: String,
      default: 'image',
    },
    content1: {
      type: String,
      default: 'Customer Feedback',
    },
    stat4Description: {
      type: String,
      default: 'consectetur adipiscing.',
    },
  },
}
</script>

<style scoped>
.stats2-container {
  width: 100%;
  flex-direction: column;
}
.stats2-max-width {
  gap: var(--dl-space-space-twounits);
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.stats2-container2 {
  align-self: center;
}
.stats2-container3 {
  width: 100%;
}
.stats2-container4 {
  align-items: flex-start;
}
.stats2-container5 {
  align-items: flex-start;
}
.stats2-container6 {
  width: 100%;
}
.stats2-container7 {
  align-items: flex-start;
}
.stats2-container8 {
  align-items: flex-start;
}
@media(max-width: 991px) {
  .stats2-max-width {
    gap: var(--dl-space-space-twounits);
    flex-direction: column;
  }
}
@media(max-width: 479px) {
  .stats2-image {
    width: 100%;
  }
}
</style>
