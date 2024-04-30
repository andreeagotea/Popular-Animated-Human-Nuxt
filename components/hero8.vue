<template>
  <div class="hero8-header26 thq-section-padding"
    ><div class="hero8-max-width thq-flex-column thq-section-max-width"
      ><div class="hero8-column"
        ><div class="hero8-content"
          ><h1 class="hero8-text thq-heading-1">{{ heading1 }}</h1
          ><p class="hero8-text1 thq-body-large">{{ content1 }}</p
          ><div class="hero8-actions"
            ><button class="thq-button-filled hero8-button"
              ><span class="thq-body-small">{{ action1 }}</span></button
            ><button class="thq-button-outline hero8-button1"
              ><span class="thq-body-small">{{ action2 }}</span></button
            ></div
          ></div
        ></div
      ><img :alt="image1Alt" :src="image1Src" class="thq-img-ratio-16-9" /></div
  ></div>
</template>

<script>
export default {
  name: 'Hero8',
  props: {
    action2: {
      type: String,
      default: 'Secondary action',
    },
    image1Alt: {
      type: String,
      default: 'Image',
    },
    action1: {
      type: String,
      default: 'Main action',
    },
    image1Src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1552083974-186346191183?ixid=M3w5MTMyMXwwfDF8c2VhcmNofDE1fHxhYnN0cmFjdHxlbnwwfHx8fDE3MTA4NzA5MzB8MA&ixlib=rb-4.0.3&w=1400',
    },
    heading1: {
      type: String,
      default: 'Catchy and impactful hero headline',
    },
    content1: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat.',
    },
  },
}
</script>

<style scoped>
.hero8-header26 {
  gap: var(--dl-space-space-twounits);
}
.hero8-max-width {
  align-self: center;
}
.hero8-column {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-items: center;
  flex-shrink: 0;
  flex-direction: column;
}
.hero8-content {
  gap: var(--dl-space-space-oneandhalfunits);
  width: 100%;
  display: flex;
  align-self: stretch;
  align-items: center;
  flex-direction: column;
}
.hero8-text {
  text-align: center;
}
.hero8-text1 {
  text-align: center;
}
.hero8-actions {
  gap: var(--dl-space-space-unit);
  display: flex;
  align-items: flex-start;
}
@media(max-width: 479px) {
  .hero8-actions {
    width: 100%;
    flex-direction: column;
  }
  .hero8-button {
    width: 100%;
  }
  .hero8-button1 {
    width: 100%;
  }
}
</style>
