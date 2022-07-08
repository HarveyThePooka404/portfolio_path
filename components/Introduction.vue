<template>
    <div>
        <h1 class="main-title"> Welcome, Input ! </h1>
        <p class="text-align-center"> How can I help you today? </p>
        <div class="nav-menu">
            <span class="title"> Career </span>
            <span class="title"> CV </span>
            <span class="title"> Contact </span>
        </div>
    </div>
</template>

<style lang="scss" scoped>

.main-title {
    font-size: 5rem;
    text-align: center;
    line-height: 1em;
}

.text-align-center {
    text-align: center;
}

.nav-menu {
    display: flex;
    width: 100%;
    flex-wrap: wrap;

    @media (max-width: 768px)  {
        flex-flow: column;
        justify-content: space-around;
    }
}

span {
    list-style-type: none;
    margin-left: 20%;
    font-size: 2.5rem;
    &:hover {
        text-decoration: underline;
        cursor: pointer;
    }
}

</style>