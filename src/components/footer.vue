<script>
export default {
    name: 'footerApp'
}
</script>
<template>
    <div class="img_footer"> <img src="../../public/img/sabackground.png" alt="s" srcset=""> </div>

    <footer>
        <div class="right">
            <p>© copyright | </p>
        </div>

        <div class="left">
            <p><a href="https://github.com/Jacksonpirlo">Jackson Florez</a></p>
        </div>
    </footer>
</template>

<style scoped>

.img_footer img {
    width: 100%;
}

footer {
    display: flex;
    background-color: rgb(32, 139, 32);
    justify-content: center;
    text-align: center;
}

.right p {
    color: white;
}


.left p a {
    color: white;
    text-decoration: none;
    margin-left: 10px;
}
</style>