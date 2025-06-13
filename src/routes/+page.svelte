<script>
    import { onMount } from 'svelte';
    import { copy } from 'svelte-copy';
</script>

<header class="fixed w-full py-4 px-4 shadow-sm">
    <!-- Navbar -->
    <nav class="flex justify-between">
        <h1>GUS COCHRAN</h1>
        <!-- Contacts -->
        <div class="flex items-center gap-7">
            <h1>HOME</h1>
            <h1>WORK</h1>
            <!-- Email -->
            <a aria-label="Copy my Email!" class="cursor-pointer" href="mailto:guscochran77@gmail.com">
                <i class="fa-solid fa-square-envelope fa-xl"></i>
            </a>
            
            <!-- Linkedin -->
            <a aria-label="Linkedin" href="https://www.linkedin.com/in/gus-cochran/" target="_blank">
                <i class="fa-brands fa-linkedin fa-xl cursor-pointer"></i>
            </a>
                
            <!-- Instagram -->
            <a aria-label="Instagram" href="https://www.instagram.com/gus.f.c/" target="_blank">
                <i class="fa-brands fa-instagram fa-xl cursor-pointer"></i>
            </a>
            
            <!-- Github -->
            <a aria-label="Github" href="https://github.com/UOGus" target="_blank">
                <i class="fa-brands fa-square-github fa-xl cursor-pointer"></i>
            </a>
            
        </div>
        
    </nav>
</header>
