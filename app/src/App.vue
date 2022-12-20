<script setup>
import Video from "./components/Video.vue";
import Header from "./components/Header.vue";
import { GithubOutlined, SlackOutlined, TwitterOutlined, FileSearchOutlined } from '@ant-design/icons-vue';
</script>

<template>
  <div>
    <a-row>
      <Header />
    </a-row>
    <div style="margin-left:auto;margin-right:auto;width:100%;">
      <a-row style="max-width:1024px;margin-left:auto;margin-right:auto;">
        <a-col span="16">
          <div>
            <Video />
          </div>
        </a-col>
        <a-col :span="8">
          <div>
            <a-button type="primary" size="large">
              <template #icon>
                <img style="width:21px;margin-right: 5px;" src="./assets/logo_white_transparent.svg" />
              </template>
              Introducing FeatBit
            </a-button>
            <br />
            <br />
            <a-button type="primary" size="large">
              <template #icon>
                <github-outlined />
              </template>
              Star us on GitHub
            </a-button>
            <br />
            <br />
            <a-button type="primary" size="large">
              <template #icon>
                <file-search-outlined />
              </template>
              Documentation
            </a-button>
            <br />
            <br />
            <a-button type="primary" size="large">
              <template #icon>
                <slack-outlined />
              </template>
              Online Support
            </a-button>
            <br />
            <br />
            <a-button type="primary" size="large">
              <template #icon>
                <twitter-outlined />
              </template>
              Twitter
            </a-button>

          </div>
        </a-col>
      </a-row>
    </div>
    <div style="margin-top:30px;text-align: center;">
      FeatBit is an #OpenSource software.
      Copyright © 2022 HeartBit
    </div>
  </div>
</template>

<style scoped>

</style>
