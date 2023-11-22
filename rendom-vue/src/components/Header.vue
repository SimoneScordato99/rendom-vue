<script setup>
import { store } from "../store.js";
</script>

<template>
    <div class="box">
        <div class="box-logo">
            <img src="../../public/Immagine 2023-11-21 160218.png" alt="logo">
        </div>
        <div class="box-navigazione">
            <ul>
                <li>mario</li>
                <li>mario</li>
                <li>mario</li>
                <li>mario</li>
                <li>mario</li>
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
    .box{
        width: 100%;
        height: 200px;
        .box-logo{
            height: 200px;
            img{
                height: 100%;
            }
        }
        .box-navigazione{
            background-color: black;
            color: white;
            
            ul{
                display: flex;
                justify-content: space-around;
                margin: 0;
                padding: 5px 0;
                li{
                    list-style-type: none;
                    text-transform: uppercase;

                }
            }
        }
    }
</style>