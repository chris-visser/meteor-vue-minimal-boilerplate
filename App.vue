<template>
  <main>
    <TheHeader />

    <p>
      This is a Vue application built in Meteor. It's very basic and to illustrate that Meteor and Vue go hand in hand without any configuration.
    </p>
    <p>
      It follows a basic setup with only the Vue router and 1 package that allows us to write Vue component files in Meteor.
    </p>
  </main>
</template>

<script>
  import TheHeader from './components/TheHeader';

  export default {
    components: {
      TheHeader,
    }
  }
</script>
