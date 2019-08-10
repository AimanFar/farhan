<template>
    <div class="navbar">
        <div class="navbar-start">
            <div class="navbar-brand">
                <a class="navbar-item" href="/">
                    <img src="../assets/img/farhan.svg" alt="" width="115">
                </a>
            </div>
        </div>

        <div class="navbar-end navbar-menu">
            <p class="navbar-item is-size-7 has-text-weight-bold has-text-black">
                1800-456-959
            </p>
        </div>
    </div>
</template>


<script>
    export default {
        name: 'Nav',
        data: function () {
            return {
                showNav: false
            }
        }

    }
</script>