<script>
    import SectionWrapper from "./sectionWrapper.svelte";
    import Header from "../components/header.svelte";
    import CtAs from "./CTAs.svelte";
</script>

<SectionWrapper>
    <Header />
    <div class="flex flex-col gap-10 flex-1 items-center justify-center pb-10 md:pb-14">
        <h2 class="text-5xl sm:text-6xl md:text-7xl lg: max-w-[1200px] mx-auto w-full text-center font-semibold">
            <span class="text-indigo-400">Full-Stack</span> Applications
            <span class="text-slate-600 line-through">Are Hard</span><br />
            Just Got <span class="text-indigo-400">Easier</span>
        </h2>
        <p class="text-xl sm:text-2xl md:text-3xl text-center max-w-[1000px] mx-auto w-full">
            Less worrying & more doing. We make your <span class="italic">ideas into a reality</span>.
        </p>
        <CtAs />
    </div>
</SectionWrapper>