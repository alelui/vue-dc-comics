<template>
    <header>
        <nav>
            <img src="../assets/img/dc-logo.png" alt="">
            <ul>
                <li><a href="#">home</a></li>
                <li><a href="#">home</a></li>
                <li><a href="#">home</a></li>
                <li><a href="#">home</a></li>
                <li><a href="#">home</a></li>
                <li><a href="#">home</a></li>
                <li><a href="#">home</a></li>
            </ul>

        </nav>
    </header>
</template>

<script>
    export default {
        name: 'Header'
    }
</script>

<style lang="scss" scoped>
    header{
        height: 70px;

        nav{
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 60%;
            height: 100%;
            margin: 0 auto;
            padding: 10px;
            background-color: blanchedalmond;

            img{
                height: 50px;
            }

            ul li{
                display: inline-block;
                margin: 0 10px;

                a{
                    text-decoration: none;
                    text-transform: uppercase;
                }
            }
        }
    }
</style>
