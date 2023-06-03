<template>
  <div class="gallery-card1-gallery-card" v-bind:class="rootClassName">
    <img :alt="image_alt" :src="image_src" class="gallery-card1-image" />
    <h2 class="gallery-card1-text">{{ title }}</h2>
    <span class="gallery-card1-text1">{{ subtitle }}</span>
  </div>
</template>

<script>
export default {
  name: 'GalleryCard1',
  props: {
    image_alt: {
      type: String,
      default: 'image',
    },
    rootClassName: String,
    image_src: {
      type: String,
      default:
        'https://images.unsplash.com/photo-1418065460487-3e41a6c84dc5?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDEyfHxmb3Jlc3R8ZW58MHx8fHwxNjI2MjUxMjg4&ixlib=rb-1.2.1&w=1500',
    },
    title: {
      type: String,
      default: 'Project Title',
    },
    subtitle: {
      type: String,
      default: 'Lorem ipsum dolor sit amet',
    },
  },
}
</script>

<style scoped>
.gallery-card1-gallery-card {
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.gallery-card1-image {
  width: 100%;
  height: 280px;
  object-fit: cover;
  border-color: var(--dl-color-light-color5);
  border-width: 5px;
  border-radius: var(--dl-radius-radius-radius8);
  background-color: var(--dl-color-gray-500);
}
.gallery-card1-text {
  align-self: flex-start;
  margin-top: var(--dl-space-space-halfunit);
  font-weight: 600;
  margin-bottom: var(--dl-space-space-halfunit);
}
.gallery-card1-text1 {
  color: var(--dl-color-gray-500);
  align-self: flex-start;
}



.gallery-card1-root-class-name3 {
  height: auto;
}


@media(max-width: 767px) {
  .gallery-card1-gallery-card {
    flex-direction: column;
  }
}
@media(max-width: 479px) {
  .gallery-card1-image {
    height: 10rem;
  }
}
</style>
