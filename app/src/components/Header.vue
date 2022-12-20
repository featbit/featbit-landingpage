
<script setup>
import { GithubOutlined, SlackOutlined, TwitterOutlined, FileSearchOutlined } from '@ant-design/icons-vue';

defineProps({
    msg: {
        type: String,
        required: true,
    },
});
</script>

<template>
    <div class="header-layout">
        <div class="header-logo">
            <a-row style="margin-left: auto;margin-right: auto;max-width:380px;">
                <a-col span="7" class="header-title">
                    <img style="width:90%;margin-right: 35px;" src="../assets/featbit02.png" />
                </a-col>
                <a-col span="17" class="header-title">
                    <h1 style="font-size:60px;margin-bottom:0px;">FeatBit</h1>
                </a-col>
            </a-row>
        </div>
        <a-row>
            <p style="margin-left:auto;margin-right:auto;max-width:618px;text-align:center;">
                A scalable and high-performance Feature Management platform that empowers all teams to deliver, control,
                experiment with and monetize their software.
            </p>
        </a-row>
        <div class="header-btns">
        </div>
    </div>
</template>

<style scoped>
.header-layout {
    width: 100%;
    margin-left: auto;
    margin-right: auto;

}

.header-title {
    width: 100%;
    margin-left: auto;
    margin-right: auto;
}

.header-logo {
    margin-left: auto;
    margin-right: auto;
    margin-top: 10px;
    margin-bottom: 25px;
    display: flex;
}

.header-title h1 {
    margin-left: auto;
    margin-right: auto;
}

.header-btns {
    margin-left: auto;
    margin-right: auto;
    margin-top: 10px;
    margin-bottom: 15px;
    display: flex;
}
@media (min-width: 1024px) {}
</style>
