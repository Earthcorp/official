<template>
    <div class="sm:m-6 space-y-6">
        <div class="relative bg-skin-fill max-w-4xl mx-auto overflow-hidden sm:rounded-2xl">
            <img class="absolute inset-0 h-full w-full object-cover opacity-60" src="~assets/img/banner.jpg" alt="Banner">
            <div class="absolute inset-0 bg-gradient-to-br from-skin-hue via-skin-hue to-transparent opacity-90"></div>
            <div class="relative max-w-2xl mx-auto text-center py-16 px-4 sm:py-20 sm:px-6 lg:px-8">
                <h2 class="text-3xl font-extrabold text-skin-base sm:text-4xl">
                    <a href="https://web.earthcorp.in"><img class="block mx-auto h-14 sm:mx-auto sm:flex-shrink-0 mb-3" src="~assets/img/logo.svg" alt="Earthcorp"></a>
                    <span class="block">We develop digital solutions</span>
                </h2>
                <p class="mt-4 text-lg leading-6 text-skin-muted">We are a passionate, results-oriented digital marketing team based in India. We provide end-to-end website design, development and digital marketing solutions that focus on the goals and objectives of the customer, from strategy and design to internet marketing. Our team of experts provide success to the client on each project assigned. We support you in exceeding your expectations.</p>
                <div class="mt-10 max-2-sm mx-auto sm:max-w-none sm:flex sm:justify-center">
                    <div class="space-y-4 sm:space-y-0 sm:mx-auto sm:inline-grid sm:grid-cols-2 sm:gap-5">
                        <a href="#" class="text-skin-inverted bg-skin-button-accent hover:bg-skin-button-accent-hover flex items-center justify-center px-4 py-3 border border-transparent text-base font-semibold rounded-md shadow-sm sm:px-8"> Get started </a>
                        <a href="#" class="text-skin-base bg-skin-button-muted flex items-center justify-center px-4 py-3 border border-transparent text-base font-semibold rounded-md shadow-sm bg-opacity-60 hover:bg-opacity-70 sm:px-8" id="Switch"> Live demo </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        head () {
            return {
                script: [{
                    src: 'https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js',
                    'data-ad-client': "ca-pub-1435402359967609",
                    async: true
                }]
            }
        }
    }
</script>

<style scoped>
    
</style>