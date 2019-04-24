<template>
    <header class="header-container d-flex align-items-center justify-content-between px-3">
        <ul class="links-container d-flex align-items-center mb-0 pl-0">
            <li><a href="">Link</a></li>
            <li><a href="">Link</a></li>
            <li><a href="">Link</a></li>
            <li><a href="">Link</a></li>
            <li><a href="">Link</a></li>
        </ul>
        <a href="" class="make-a-book hotdog ff-oswald">Make a book</a>
    </header>
</template>

<script>
export default {

}
</script>
<style lang="scss" scoped>
    header.header-container {
        height: 80px;
        background: gray;
        border-bottom: 1px solid darkgray;
    }
    ul.links-container {
        list-style-type: none;
    }
    li {
        display: inline-block;
        margin: 0 1rem;
    }
    a {
        transition: all 0.15s ease-in-out;
        font-family: 'Oswald', 'Arial', sans-serif;
        text-transform: uppercase;
        letter-spacing: 0.45px;
        color: white;
    }
</style>
