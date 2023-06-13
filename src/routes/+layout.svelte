<div class="navbar">
    <h2>Welcome to My site</h2>
</div>
<div class="scene">
    <slot class="three-space"/>
</div>

<style lang="scss">
    .navbar {
        display: flex;
        position: sticky;
        top: 0;
        z-index: 3;
        height: 64px;
        background-color: #2b2b2b;
        padding: 0 32px 0 32px;
    }

    .scene {
        width: 100%;
        height: 100%;
        position: absolute;
        inset: 0;
        background-color: lightblue;
    }
</style>