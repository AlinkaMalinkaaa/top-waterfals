<script>

import Hero from '@/components/Hero.vue';
import Navbar from '@/components/Navbar.vue';
import Packages from '@/components/Packages.vue';
import Reason from '@/components/Reason.vue';
import Review from '@/components/Review.vue';
import Footer from '@/components/Footer.vue';

export default {
    components: {
        Hero,
        Navbar,
        Packages,
        Reason,
        Review,
        Footer
    },
};

</script>
<template>
    <Navbar />
    <Hero />
    <Packages />
    <Reason />
    <Review />
    <Footer />
  
</template>