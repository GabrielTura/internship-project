<template>
<div class="tes">
    <section>
        <b-dropdown aria-role="list">
            <button class="button" slot="trigger">
                <img class="avatar" src="../assets/admin.svg"/>
                <span>Click me!</span>
            </button>

            <b-dropdown-item aria-role="listitem">Action</b-dropdown-item>
            <b-dropdown-item aria-role="listitem">Another action</b-dropdown-item>
            <b-dropdown-item aria-role="listitem">Something else</b-dropdown-item>
        </b-dropdown>
    </section>
</div>
</template>

<style>
    .tes {
        position: fixed;
        top: 0;
        width: 100%;
        margin-left: 33.33vh;
    }
</style>
