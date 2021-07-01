<script>
import {onMount} from 'svelte'
onMount(() => {
    window.$('.teams').slick({
        dots: true,
        infinite: true,
        slidesToShow: 4,
        slidesToScroll: 1,
        autoplay: true,
        autoplaySpeed: 3000,
        responsive: [
            {
                breakpoint: 1024,
                settings: {
                    slidesToShow: 4,
                    slidesToScroll: 1,
                    infinite: true,
                    dots: true
                }
            },
                
            {
                breakpoint: 600,
                settings: {
                    slidesToShow: 3,
                    slidesToScroll: 1,
                    infinite: true,
                    dots: true
                }
            },
            {
                breakpoint: 480,
                settings: {
                    slidesToShow: 1,
                    slidesToScroll: 1,
                    infinite: true,
                    dots: true
                }
            }
        ]
    });


    window.$('.testimonials').slick({
        dots: true,
        infinite: true,
        slidesToShow: 1,
        adaptiveHeight: true,
        autoplay: true,
        autoplaySpeed: 3000,
    });
	
		
});
</script>
<svelte:head>
    <title>Learnoflix Affiliate Program - LAP</title>
</svelte:head>
<main class="m-0 py-8 bg-black w-full min-h-screen">

    <header class="flex justify-between items-center w-12/12 px-6 md:px-16">
        <div class="w-32 h-18">
            <img src="./public/images/logo.png" alt="Logo" class="w-32 h-18"/>
        </div>
        <div class="hidden md:inline-block">
            <a href="/" class="text-white uppercase font-bold text-white text-lg mx-4 lg:px-4">Home</a>
            <a href="/" class="text-white uppercase font-bold text-white text-lg mx-4 lg:px-4">About Us</a>
            <a href="/" class="text-white uppercase font-bold text-white text-lg mx-4 lg:px-4">Contact Us</a>
        </div>
        <div class="flex jusitfy-end">
            <div class="hidden md:inline-block">
                <a href="/" class="text-white uppercase font-bold text-white text-lg">Sign in</a>
            </div>
            <div class="flex items-center md:hidden">
                <i class="fa fa-bars fa-2x text-white"></i>
            </div>
        </div>
    </header>

    <section class="md:flex md:justify-start md:items-center w-12/12 my-16 px-6 md:px-16">
        <div class="w-12/12 md:w-4/12 xl:w-3/12 my-5">
            <div class="mr-5">
                <h1 class="text-4xl text-white uppercase font-extrabold">
                    START <br>LEARNING NOW
                </h1>
                <h4 class="text-lg font-light text-gray-200">
                    Learn from the best of coaches
                </h4>
                <div class="mt-16">
                    <button type="button" class="bg-teal-primary py-4 px-6 xl:px-20 text-center text-white font-extrabold text-xl uppercase">Start Now</button>
                </div>
            </div>
        </div>
        <div class="relative w-12/12 md:w-8/12 xl:w-9/12 my-5 mx-auto" style="height: 480px;">
            <div class="plyr__video-embed w-full h-full absolute" id="player">
                <iframe src="https://www.youtube.com/embed/bTqVqk7FSmY" allowtransparency allow="autoplay"></iframe>
            </div>
        </div>
    </section>

    <section class="mb-16 w-12/12 px-6 md:px-16">
        <div class="teams">
            <div class="mx-4 bg-transparent">
                <div>
                    <div class="flex justify-center mx-auto">
                        <img src="./public/images/sam-harvard-1.jpg" alt="Sam Harvard"/>
                    </div>
                    <div class="bg-black opacity-80 z-50 -mt-24 h-32">
                        <h1 class="text-white text-center text-2xl sm:text-xl lg:text-4xl font-normal uppercase" style="font-family: Playfair Display SC;">SAM HARVARD</h1>
                        <h3 class="text-white text-center font-bold text-lg sm:text-sm lg:text-lg" style="font-family: Roboto;">The billonaire mentor</h3>
                    </div>
                </div>
            </div>

            <div class="mx-4 bg-transparent">
                <div>
                    <div class="flex justify-center mx-auto">
                        <img src="./public/images/temi-ajibewa.jpg" alt="Temi Ajibewa"/>
                    </div>
                    <div class="bg-black opacity-80 z-50 -mt-24 h-32">
                        <h1 class="text-white text-center text-2xl sm:text-xl lg:text-4xl font-normal uppercase" style="font-family: Playfair Display SC;">TEMI AJIBEWA</h1>
                        <h3 class="text-white text-center font-bold text-lg sm:text-sm lg:text-lg" style="font-family: Roboto;">The Coach of coaches</h3>
                    </div>
                </div>
            </div>

            <div class="mx-4 bg-transparent">
                <div>
                    <div class="flex justify-center mx-auto">
                        <img src="./public/images/kenny-nwokoye.jpg" alt="Kenny Nwokoye"/>
                    </div>
                    <div class="bg-black opacity-80 z-50 -mt-24 h-32">
                        <h1 class="text-white text-center text-2xl sm:text-xl lg:text-4xl font-normal uppercase" style="font-family: Playfair Display SC;">KENNY NWOKOYE</h1>
                        <h3 class="text-white text-center font-bold text-lg sm:text-sm lg:text-lg" style="font-family: Roboto;">Organic commando</h3>
                    </div>
                </div>
            </div>

            <div class="mx-4 bg-transparent">
                <div>
                    <div class="flex justify-center mx-auto">
                        <img src="./public/images/sam-harvard-2.jpg" alt="Sam Harvard"/>
                    </div>
                    <div class="bg-black opacity-80 z-50 -mt-24 h-32">
                        <h1 class="text-white text-center text-2xl sm:text-xl lg:text-4xcenterl font-normal uppercase" style="font-family: Playfair Display SC;">SAM HARVARD</h1>
                        <h3 class="text-white text-center font-bold text-lg sm:text-sm lg:text-lg" style="font-family: Roboto;">The billonaire mentor</h3>
                    </div>
                </div>
            </div>

            <div class="mx-4 bg-transparent">
                <div>
                    <div class="flex justify-center mx-auto">
                        <img src="./public/images/sam-harvard-2.jpg" alt="Sam Harvard"/>
                    </div>
                    <div class="bg-black opacity-80 z-50 -mt-24 h-32">
                        <h1 class="text-white text-center text-2xl sm:text-xl lg:text-4xl font-normal uppercase" style="font-family: Playfair Display SC;">SAM HARVARD</h1>
                        <h3 class="text-white text-center font-bold text-lg sm:text-sm lg:text-lg" style="font-family: Roboto;">The billonaire mentor</h3>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <section class="mb-16 w-12/12 flex justify-start items-center px-6 md:px-16">
        <div class="mr-5 w-12/12 md:w-5/12 xl:w-4/12">
            <h4 class="mb-6 text-white font-extrabold text-xl">Get 100+ classes across different categories</h4>
            <p class="text-white text-md font-normal my-4 flex items-center">
                <i class="fa fa-check-double"></i>
                <span class="mx-5">Access to seasoned trainers  and coaches</span>
            </p>
            <p class="text-white text-md font-normal my-4 flex items-center">
                <i class="fa fa-check-double"></i>
                <span class="mx-5">Pre-recorded videos you can watch at your own pace</span>
            </p>
            <p class="text-white text-md font-normal my-4 flex items-center">
                <i class="fa fa-check-double"></i>
                <span class="mx-5">Weekly Zoom meetings with Top Industry experts</span>
            </p>
            <p class="text-white text-md font-normal my-4 flex items-center">
                <i class="fa fa-check-double"></i>
                <span class="mx-5">Available on windows, andriod and ios</span>
            </p>
            <div class="flex justify-start items-center mt-8">
                <div class="mr-4">
                    <img src="./public/images/google-store.png" alt="Download on googleplay store"/>
                </div>
                <div>
                    <img src="./public/images/apple-store.png" alt="Download on apple app store"/>
                </div>
            </div>
        </div>
        <div class="hidden md:flex md:justify-between md:w-7/12 xl:w-8/12">
            <div class="mx-4">
                <img src="./public/images/phone-1.png" alt="Download on andriod"/>
            </div>
            <div class="mx-4">
                <img src="./public/images/phone-2.png" alt="Download on apple"/>
            </div>
            <div class="mx-4">
                <img src="./public/images/tab.png" alt="Download on tablet"/>
            </div>
        </div>
    </section>

    <section class="mb-16 w-12/12 px-6 md:px-16">
        <div class="testimonials">
           
            <div class="mx-5 md:mx-10 xl:mx-60 w-12/12">
                <div class="flex justify-center">
                    <div>
                        <div class="flex justify-start items-center">
                            <div class="w-full md:w-2/3 xl:w-2/3 bg-gray-800 text-gray-100 text-lg p-5 md:p-10 xl:p-16 font-light z-50">
                                <p>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo vitae quae quos quas quisquam placeat veniam nam corporis ut nemo! Alias blanditiis aliquam laborum unde quibusdam in, nobis fugiat temporibus?
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores incidunt nulla ullam dolor tenetur voluptatibus, fugiat voluptates unde. Maiores ipsam aspernatur illum quam provident? Omnis aperiam assumenda ipsa eaque error.
                                </p>
                                <div class="mt-6 flex items-center">
                                    <div class="inline-block md:hidden mr-4 w-12 h-12">
                                        <img src="./public/images/ada.jpg" class="w-full h-full rounded-full" alt="ada"/>
                                    </div>
                                    <b class="font-bold">Adaa Billions</b>, <small>Nigeria</small>
                                </div>
                            </div>
                            <div class="hidden md:inline-block md:w-1/3 xl:w-1/3 md:-ml-10 xl:-ml-20">
                                <img src="./public/images/ada.jpg" class="w-full rounded" style="height: 480px;" alt="ada"/>
                            </div>
                        </div>
                    </div>

                </div>
            </div>

            <div class="mx-5 md:mx-10 xl:mx-60 w-12/12">
                <div class="flex justify-center">
                    <div>
                        <div class="flex justify-start items-center">
                            <div class="w-full md:w-2/3 xl:w-2/3 bg-gray-800 text-gray-100 text-lg p-5 md:p-10 xl:p-16 font-light z-50">
                                <p>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo vitae quae quos quas quisquam placeat veniam nam corporis ut nemo! Alias blanditiis aliquam laborum unde quibusdam in, nobis fugiat temporibus?
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores incidunt nulla ullam dolor tenetur voluptatibus, fugiat voluptates unde. Maiores ipsam aspernatur illum quam provident? Omnis aperiam assumenda ipsa eaque error.
                                </p>
                                <div class="mt-6 flex items-center">
                                    <div class="inline-block md:hidden mr-4 w-12 h-12">
                                        <img src="./public/images/ada.jpg" class="w-full h-full rounded-full" alt="ada"/>
                                    </div>
                                    <b class="font-bold">Adaa Billions</b>, <small>Nigeria</small>
                                </div>
                            </div>
                            <div class="hidden md:inline-block md:w-1/3 xl:w-1/3 md:-ml-10 xl:-ml-20">
                                <img src="./public/images/ada.jpg" class="w-full rounded" style="height: 480px;" alt="ada"/>
                            </div>
                        </div>
                    </div>

                </div>
            </div>

            <div class="mx-5 md:mx-10 xl:mx-60 w-12/12">
                <div class="flex justify-center">
                    <div>
                        <div class="flex justify-start items-center">
                            <div class="w-full md:w-2/3 xl:w-2/3 bg-gray-800 text-gray-100 text-lg p-5 md:p-10 xl:p-16 font-light z-50">
                                <p>
                                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo vitae quae quos quas quisquam placeat veniam nam corporis ut nemo! Alias blanditiis aliquam laborum unde quibusdam in, nobis fugiat temporibus?
                                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Asperiores incidunt nulla ullam dolor tenetur voluptatibus, fugiat voluptates unde. Maiores ipsam aspernatur illum quam provident? Omnis aperiam assumenda ipsa eaque error.
                                </p>
                                <div class="mt-6 flex items-center">
                                    <div class="inline-block md:hidden mr-4 w-12 h-12">
                                        <img src="./public/images/ada.jpg" class="w-full h-full rounded-full" alt="ada"/>
                                    </div>
                                    <b class="font-bold">Adaa Billions</b>, <small>Nigeria</small>
                                </div>
                            </div>
                            <div class="hidden md:inline-block md:w-1/3 xl:w-1/3 md:-ml-10 xl:-ml-20">
                                <img src="./public/images/ada.jpg" class="w-full rounded" style="height: 480px;" alt="ada"/>
                            </div>
                        </div>
                    </div>

                </div>
            </div>

        </div>
    </section>

    <section class="mb-16 w-12/12 md:flex justify-center items-center px-6 md:px-16">
        <div class="my-5 bg-gray-800 p-8 w-12/12 md:w-4/12 xl:w-3/12 md:mx-2 xl:mx-5">
            <h2 class="font-normal mb-2 text-white text-2xl text-center">6000+ Students</h2>
            <h4 class="font-light text-gray-300 text-lg text-center">Over 6,000 active students</h4>
        </div>

        <div class="my-5 bg-gray-800 p-8 w-12/12 md:w-4/12 xl:w-3/12 md:mx-2 xl:mx-5">
            <h2 class="font-normal mb-2 text-white text-2xl text-center">7000+ Affiliates</h2>
            <h4 class="font-light text-gray-300 text-lg text-center">Over 7,000 affiliates</h4>
        </div>

        <div class="my-5 bg-gray-800 p-8 w-12/12 md:w-4/12 xl:w-3/12 md:mx-2 xl:mx-5">
            <h2 class="font-normal mb-2 text-white text-xl text-center">40Million naira+ paid </h2>
            <h4 class="font-light text-gray-300 text-md text-center">Over 40Million naira+ paid in commission</h4>
        </div>
    </section>

    <section class="my-16 w-12/12 bg-gray-300 px-10 py-20 md:py-48 md:px-24 md:flex justify-center items-center">
        <div class="w-full md:w-5/12 xl:w-4/12">
            <h1 class="text-3xl font-extrabold text-black">WEEKLY ZOOM TRAININGS <br>
                FOR AFFILIATES</h1>
            <h4 class="text-lg mt-6 font-normal text-gray-900">Weekly zoom meetings for all affiliates with Top coaches and trainers</h4>
        </div>
        <div class="w-full md:w-7/12 xl:w-8/12">
            
        </div>
    </section>

    <footer class="w-12/12 px-6 md:px-16">
        
        <div class="flex justify-between items-start">
            <div class="w-full lg:w-5/12">
                <p class="my-4">
                    <img src="./public/images/logo.png" alt="Logo" class="w-24 h-10"/>
                </p>
                <p class="m-4 text-white font-normal">
                    LearnoFlix provides opportunity for anyone from anywhere in the world 
                    to learn from experts.
                    You can choose what you want to become and let
                    "LearnoFlix" help you become it
                </p>
            </div>
            <div class="w-full md:w-7/12 lg:w-4/12 lg:flex lg:justify-end">
                <div>
                    <p class="font-semibold text-lg text-white my-8">Useful Links</p>
                    <p class="font-normal text-md my-2 text-white">
                        <a href="/">Home</a>
                    </p>
                    <p class="font-normal text-md my-2 text-white">
                        <a href="/">About Us</a>
                    </p>
                    <p class="font-normal text-md my-2 text-white">
                        <a href="/">Contact Us</a>
                    </p>
                    <p class="font-normal text-md my-2 text-white">
                        <a href="/">Affiliate Signup</a>
                    </p>
                    <p class="font-normal text-md my-2 text-white">
                        <a href="/">Login</a>
                    </p>
                </div>

            </div>
            <div class="w-full md:w-5/12 lg:w-3/12 lg:flex lg:justify-end">
                <div>
                    <p class="font-semibold text-lg text-white my-8">Connect With Us</p>
                    <p class="font-normal text-md my-5 text-white">
                        <a href="/">
                            <i class="fab fa-facebook-square"></i>
                            <span class="ml-4">Learnoflix</span>
                        </a>
                    </p>
                    <p class="font-normal text-md my-5 text-white">
                        <a href="/">
                            <i class="fab fa-twitter"></i>
                            <span class="ml-4">Learnoflix</span>
                        </a>
                    </p>
                    <p class="font-normal text-md my-5 text-white">
                        <a href="/">
                            <i class="fab fa-instagram"></i>
                            <span class="ml-4">Learnoflix</span>
                        </a>
                    </p>
                </div>
            </div>

        </div>

        <div class="w-12/12 my-6"><hr></div>
        <div class="w-12/12 flex justify-between my-10 text-white font-semibold">
            <div>
                <a href="/" class="mr-5">Terms and Conditions</a> 
                |
                <a href="/" class="ml-5">Privacy Policy</a>
            </div>
            <div class="text-white font-normal">
                &copy;2021 copyrights. Property of LEARNOFLIX
            </div>
        </div>
    </footer>


</main>