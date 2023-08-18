<template>
  <div class="home-container">
    <img
      alt="image"
      src="https://flippin.club/wp-content/uploads/2023/07/lgo.png"
      class="home-image"
    />
    <h1 class="home-text">
      <span>FlippinGAMES</span>
      <br />
    </h1>
    <h1 class="home-text3">Your new, best game publisher.</h1>
    <a
      href="https://flippin.club/"
      target="_blank"
      rel="noreferrer noopener"
      class="home-link button FlippinDistro"
    >
      COMING SOON, UNTIL THEN CLICK HERE!
    </a>
    <div class="home-banner">
      <h1 class="home-text4">
        <span>Sign up for Launch</span>
        <br />
      </h1>
      <div class="home-container1">
        <input
          type="text"
          placeholder="Email here..."
          class="home-textinput input"
        />
        <a
          href="mailto:chase@flippin.club?subject=Interested in project"
          class="home-link1 button"
        >
          Subscribe
        </a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home',
  head: {
    title: 'Sparse Leading Hornet',
    meta: [
      {
        property: 'og:title',
        content: 'Sparse Leading Hornet',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  border-color: var(--dl-color-gray-black);
  border-width: 1px;
  flex-direction: column;
  justify-content: flex-start;
}
.home-image {
  width: 200px;
  align-self: center;
  box-shadow: 5px 5px 9px 1px #d4d4d4;
  object-fit: cover;
  border-radius: var(--dl-radius-radius-round);
}
.home-text {
  color: var(--dl-color-gray-900);
  font-size: 5em;
  font-style: normal;
  font-weight: 900;
  line-height: 3;
  text-transform: uppercase;
}
.home-text3 {
  color: var(--dl-color-gray-700);
}
.home-link {
  color: var(--dl-color-gray-900);
  font-style: normal;
  border-width: 0px;
  border-radius: var(--dl-radius-radius-radius8);
  background-color: var(--dl-color-primary-500);
}
.home-banner {
  width: 100%;
  display: flex;
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  background-size: cover;
  justify-content: space-between;
  background-image: url('https://images.unsplash.com/photo-1485628390555-1a7bd503f9fe?ixid=Mnw5MTMyMXwwfDF8c2VhcmNofDE3fHxhcmNoaXRlY3R1cmUlMjBtaW5pbWFsfGVufDB8fHx8MTYyNjE4NDA0Mg&ixlib=rb-1.2.1&w=1500');
  background-position: center;
}
.home-text4 {
  color: var(--dl-color-gray-900);
  font-size: 3rem;
  text-align: center;
  margin-bottom: var(--dl-space-space-unit);
}
.home-container1 {
  flex: 1;
  width: var(--dl-size-size-xxlarge);
  height: var(--dl-size-size-large);
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.home-textinput {
  font-size: 0.75rem;
  border-color: var(--dl-color-gray-500);
}
.home-link1 {
  color: var(--dl-color-gray-black);
  font-size: 0.75rem;
  transition: 0.3s;
  margin-left: var(--dl-space-space-unit);
  text-decoration: none;
  background-color: var(--dl-color-gray-900);
}
.home-link1:hover {
  color: var(--dl-color-gray-black);
  background-color: transparent;
}
@media(max-width: 767px) {
  .home-banner {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
}
@media(max-width: 479px) {
  .home-banner {
    padding-top: var(--dl-space-space-threeunits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-threeunits);
  }
  .home-container1 {
    align-items: center;
    flex-direction: column;
  }
  .home-link1 {
    margin-top: var(--dl-space-space-unit);
    margin-left: 0px;
  }
}
</style>
