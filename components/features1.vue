<template>
  <div class="features1-layout251 thq-section-padding"
    ><div class="features1-max-width thq-section-max-width"
      ><div class="thq-flex-row features1-section-title"
        ><div class="features1-column thq-flex-column"
          ><span class="thq-body-small">{{ slogan }}</span
          ><h2 class="thq-heading-2 features1-text1">{{ sectionTitle }}</h2></div
        ><span class="thq-body-small">{{ sectionDescription }}</span></div
      ><div class="features1-content"
        ><div class="features1-row thq-flex-row"
          ><div class="features1-feature1 thq-flex-column"
            ><img
              :alt="feature1ImageAlt"
              :src="feature1ImageSrc"
              class="thq-img-ratio-4-3 features1-feature1-image"
            /><div class="features1-content1 thq-flex-column"
              ><h3 class="thq-heading-3">{{ feature1Title }}</h3
              ><span class="thq-body-small">{{ feature1Description }}</span></div
            ></div
          ><div class="features1-feature2 thq-flex-column"
            ><img
              :alt="feature2ImageAlt"
              :src="feature2ImageSrc"
              class="thq-img-ratio-4-3 features1-feature2-image"
            /><div class="features1-content2 thq-flex-column"
              ><h3 class="thq-heading-3">{{ feature2Title }}</h3
              ><span class="thq-body-small">{{ feature2Description }}</span></div
            ></div
          ><div class="features1-feature3 thq-flex-column"
            ><img
              :alt="feature3ImageAlt"
              :src="feature3ImageSrc"
              class="thq-img-ratio-4-3 features1-feature3-image"
            /><div class="features1-content3 thq-flex-column"
              ><h3 class="thq-heading-3">{{ feature3Title }}</h3
              ><span class="thq-body-small">{{ feature3Description }}</span></div
            ></div
          ></div
        ></div
      ><div class="features1-actions"
        ><button class="thq-button-filled features1-button"
          ><span class="thq-body-small">{{ mainAction }}</span></button
        ><button class="thq-button-outline features1-button1"
          ><span class="thq-body-small">{{ secondaryAction }}</span></button
        ></div
      ></div
    ></div
  >
</template>

<script>
export default {
  name: 'Features1',
  props: {
    feature1Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    sectionTitle: {
      type: String,
      default: 'Discover the Key Features',
    },
    feature3ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1557672172-298e090bd0f1?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDEwfHxhYnN0cmFjdHxlbnwwfHx8fDE3MTA4NzA5MzB8MA&ixlib=rb-4.0.3&h=300',
    },
    feature3Title: {
      type: String,
      default: 'Explore our key features',
    },
    feature1Title: {
      type: String,
      default: 'Explore our key features',
    },
    feature1ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1574169208507-84376144848b?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDN8fGFic3RyYWN0fGVufDB8fHx8MTcxMDg3MDkzMHww&ixlib=rb-4.0.3&w=1400',
    },
    mainAction: {
      type: String,
      default: 'Main action',
    },
    feature2ImageAlt: {
      type: String,
      default: 'PlaceholderImage1314',
    },
    feature3ImageAlt: {
      type: String,
      default: 'PlaceholderImage1314',
    },
    feature2Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature1ImageAlt: {
      type: String,
      default: 'PlaceholderImage1314',
    },
    feature2ImageSrc: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1563089145-599997674d42?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDR8fGFic3RyYWN0fGVufDB8fHx8MTcxMDg3MDkzMHww&ixlib=rb-4.0.3&h=300',
    },
    slogan: {
      type: String,
      default: 'Slogan',
    },
    feature2Title: {
      type: String,
      default: 'Explore our key features',
    },
    sectionDescription: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    feature3Description: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla.',
    },
    secondaryAction: {
      type: String,
      default: 'Secondary action',
    },
  },
}
</script>

<style scoped>
.features1-layout251 {
  width: 100%;
  height: auto;
  display: flex;
  overflow: hidden;
  position: relative;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.features1-max-width {
  gap: var(--dl-space-space-threeunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.features1-column {
  flex-shrink: 0;
}
.features1-content {
  gap: 48px;
  display: flex;
  align-self: stretch;
  align-items: flex-start;
  flex-direction: column;
}
.features1-row {
  align-items: flex-start;
}
.features1-feature1 {
  flex: 1;
}
.features1-content1 {
  align-self: stretch;
  align-items: flex-start;
}
.features1-feature2 {
  flex: 1;
}
.features1-content2 {
  align-self: stretch;
  align-items: flex-start;
}
.features1-feature3 {
  flex: 1;
}
.features1-content3 {
  align-self: stretch;
  align-items: flex-start;
}
.features1-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
  padding-top: var(--dl-space-space-unit);
  padding-left: 0px;
  padding-right: 0px;
  padding-bottom: 0px;
}
@media(max-width: 991px) {
  .features1-section-title {
    flex-direction: column;
  }
  .features1-feature1-image {
    height: 260px;
  }
  .features1-feature2-image {
    height: 260px;
  }
  .features1-feature3-image {
    height: 260px;
  }
}
@media(max-width: 767px) {
  .features1-column {
    width: 100%;
  }
  .features1-text1 {
    text-align: center;
  }
  .features1-row {
    flex-direction: column;
  }
  .features1-feature1-image {
    width: 100%;
  }
  .features1-feature2 {
    width: auto;
  }
  .features1-feature2-image {
    width: 100%;
  }
  .features1-feature3 {
    width: auto;
  }
}
@media(max-width: 479px) {
  .features1-actions {
    width: 100%;
    flex-direction: column;
  }
  .features1-button {
    width: 100%;
  }
  .features1-button1 {
    width: 100%;
  }
}
</style>
