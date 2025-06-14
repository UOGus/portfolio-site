<script>
    import { onMount } from 'svelte';
    import { copy } from 'svelte-copy';
</script>

<section class="p-8">
    <div class="flex flex-col md:flex-row items-center md:items-start gap-6 md:gap-10 p-6 bg-white shadow-md rounded-xl mx-auto">
    <!-- About Me -->
    <div class="text-left md:text-left">
        <h2 class="text-2xl font-semibold mb-2">Who is Gus Cochran?</h2>
        <p class="text-gray-700">
        I'm a newly graduated Computer Science major with a strong interest in pipeline development for post production. I have experience in full stack web development, Nuke scripting using PySide, and machine learning development using PyTorch/Scikit. I’m passionate about the post production process and how teams come together to deliver a creative vision. I hope to be a part of a great project someday! 
        </p>
    </div>
    </div>

    <div class="flex justify-center gap-6 py-6">
        <a aria-label="Copy my Email!" class="cursor-pointer" href="mailto:guscochran77@gmail.com">
                <i class="fa-solid fa-square-envelope fa-xl text-green-500"></i>
        </a>
        
        <!-- Linkedin -->
        <a aria-label="Linkedin" href="https://www.linkedin.com/in/gus-cochran/" target="_blank">
            <i class="fa-brands fa-linkedin fa-xl cursor-pointer text-blue-600"></i>
        </a>
            
        <!-- Instagram -->
        <!-- <a aria-label="Instagram" href="https://www.instagram.com/gus.f.c/" target="_blank">
            <i class="fa-brands fa-instagram fa-xl cursor-pointer"></i>
        </a> -->
        
        <!-- Github -->

        <a aria-label="Github" href="https://github.com/UOGus" target="_blank">
            <i class="fa-brands fa-square-github fa-xl cursor-pointer "></i>
        </a>
    </div>

    <hr class="mx-auto w-1/3 h-2 bg-gray-400 rounded-full border-none" />

    <section class="flex flex-col items-center gap-4 py-6 rounded-xl mx-auto">
        <div class="flex justify-between bg-white p-4 rounded shadow-md w-full text-left">
            <h1>VFX for Student Film "Deliverance"</h1>
            <a aria-label="To VFX for Student Film Page" href="/deliverance" target="_blank">
                <i class="fa-solid fa-arrow-right"></i>
            </a>
        </div>
        <div class="flex justify-between bg-white p-4 rounded shadow-md w-full text-left">
            <h1>Nuke VFX Breakdown Plugin</h1>
            <a aria-label="To Nuke VFX Breakdown Plugin Page" href="/breakdown" target="_blank">
                <i class="fa-solid fa-arrow-right"></i>
            </a>
        </div>
        <!-- <div class="flex justify-between bg-white p-4 rounded shadow-md w-full text-left">
            <h1>Sentiment Analysis Using Machine Learning</h1>
            <a aria-label="To Sentiment Analysis Using Machine Learning Page" href="/sentiment-analysis" target="_blank">
                <i class="fa-solid fa-arrow-right"></i>
            </a>
        </div> -->
    </section>
</section> 

