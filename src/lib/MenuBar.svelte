<script lang="ts">
    function scrollTo(id: string) {
        const element = document.getElementById(id);
        element?.scrollIntoView({ behavior: 'smooth' });
    }
</script>

<div class="menu-bar-container">
    <div class="window">
        <div class="title-bar">
            <button aria-label="Close" class="close"></button>
            <h1 class="title">Adam Attia</h1>
            <button aria-label="Resize" class="resize"></button>
        </div>
        <div class="details-bar">
            <span on:click={() => scrollTo('about')}>About</span>
            <span on:click={() => scrollTo('skills')}>Skills</span>      
            <span on:click={() => scrollTo('experience')}>Experience</span>
      
            <span on:click={() => scrollTo('contact')}>Contact</span>
        </div>
    </div>
</div>

<style>
    .menu-bar-container {
        position: fixed;
        top: 8px;
        left: 8px;
        right: 8px;
        z-index: 1000;
    }
    
    .menu-bar-container .window {
        width: 100%;
        margin: 0;
    }
    
    .details-bar span {
        cursor: pointer;
        padding: 2px 8px;
    }
    
    .details-bar span:hover {
        background: #000;
        color: #fff;
    }
</style>
