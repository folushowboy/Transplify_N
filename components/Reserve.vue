<template>
    <div>
         <section class="hero">
            <div class="hero-image">
                <img src="/assets//images/car.jpg" alt="Charter Bus">
            </div>

            <div class="charter-text-content">
                <!-- <span class="icon"><img src="./img/Group (1).png" alt=""></span> -->
                <h2>  Reserve</h2>
                <p class="charter-description">Book professional bus services for weddings, events, corporate functions, religious gatherings, tourism, and more.</p>
                <ul class="charter-features">
                    <li><NuxtLink to="">Wide range of vehicles including Toyota Sienna, Prado, etc.</NuxtLink> </li>
                    <li> <NuxtLink to="">Flexible booking options for any group size</NuxtLink></li>
                    <li> <NuxtLink to="">Available for single trips or multi-day events</NuxtLink></li>
                    <!-- <li>Real-time tracking of your shipment </li>
                     <li>Flexible scheduling options </li>
                   <li>Nationwide coverage with competitive rates </li> -->

                </ul>
              
              
                <div class="hero-buttons">

                 <AppButton/>

                </div>
            </div>
          

        </section>
      
    </div>
</template>

<script setup>
import '~/assets/css/Reserve.css'
</script>

<style scoped>

</style>