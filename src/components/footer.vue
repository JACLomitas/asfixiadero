<script>
export default {
    name: 'footerApp'
}
</script>
<template>
    <div class="img_footer"> <img src="../../public/img/sabackground.png" alt="" srcset=""> </div>

    <footer>
        <div class="right">
            <p>Todos los derechos reservados | 2025</p>
        </div>

        <div class="left">
            <p><a href="#">Jackson Florez</a></p>
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

/* .rigth {
    display: flex;
    flex-direction: column;
} */
</style>