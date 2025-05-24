<template>
    <div>
        <header>
            <img src="/assets/logo.jpg" alt="" class="logo" />
            <div class="menu-toggle" @click="toggleMenu">
                <div></div>
                <div></div>
                <div></div>
            </div>
            <nav>
                <ul>
                    <li>
                        <NuxtLink to="/">Charter</NuxtLink>
                        <NuxtLink to="/">FreightFlow</NuxtLink>
                        <NuxtLink to="/">Reserve</NuxtLink>
                    </li>

                    <button class="header-btn">Get Started</button>
                </ul>
            </nav>
        </header>

        <div>
            <slot />
        </div>

        <footer>

            <footer class="footer">
                <div class="footer-column">
                    <img src="/assets/logo.jpg" alt="" class="logo" />
                    <p>Connecting you with reliable,
                        vetted, and affordable transportation
                        and logistics solutions.
                    </p>
                    <div class="socials">
                        <ul>
                            <li>
                                <NuxtLink to="/"><img src="/assets/facebook.svg" alt=""></NuxtLink>
                                <NuxtLink to="/"><img src="/assets/x.svg" alt=""></NuxtLink>
                                <NuxtLink to="/"><img src="/assets/youtube.svg" alt=""></NuxtLink>
                                <NuxtLink to="/"><img src="/assets/linkdin.svg" alt=""></NuxtLink>
                            </li>
                        </ul>

                    </div>
                </div>
                <div class="footer-column">
                    <h3>Services</h3>
                    <ul>
                        <li>
                            <NuxtLink to="/">Charter</NuxtLink> <br>
                            <NuxtLink to="/">FreightFlow</NuxtLink><br>
                            <NuxtLink to="/">Reserve</NuxtLink><br>
                        </li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Company</h3>
                    <ul>
                        <li>
                            <NuxtLink to="/">About Us</NuxtLink><br>
                            <NuxtLink to="/">Our Team</NuxtLink><br>
                            <NuxtLink to="/">Testimonials</NuxtLink><br>
                            <NuxtLink to="/">Careers</NuxtLink><br>
                        </li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Legal</h3>
                    <ul>
                        <li>
                            <NuxtLink to="/">Privacy Policy</NuxtLink><br>
                            <NuxtLink to="/">Terms of Service</NuxtLink><br>
                            <NuxtLink to="/">Testimonials</NuxtLink><br>
                            <NuxtLink to="/">Cookies Policies</NuxtLink><br>
                        </li>
                    </ul>
                </div>
            </footer>

            <div class="footer-bottom">
                &copy; 2025 Transplify. All rights reserved.
            </div>

        </footer>
    </div>
</template>

<script setup>
import '~/assets/css/app.css'
function toggleMenu() {
    document.querySelector('nav ul').classList.toggle('active');
}

</script>

<style scoped> </style>