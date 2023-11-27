<template>
  <q-page padding>
    <section class="q-col-gutter-x-xl row q-py-lg">
      <div class="col-12 col-sm-auto q-py-md flex-center">
        <q-avatar size="150px">
          <q-img src="/profile.png" />
        </q-avatar>
      </div>
      <div class="col-grow column justify-between">
        <div class="row items-center">
          <span class="text-h6 text-weight-bold">kkkkinderjoy</span>
          <q-space />
          <div class="q-gutter-x-sm">
            <q-btn outline color="secondary" label="프로필 편집" />
            <q-btn flat color="secondary" icon="more_horiz" />
          </div>
        </div>
        <div class="q-gutter-x-lg">
          <span>게시물 17</span>
          <span>팔로워 200</span>
          <span>팔로잉 243</span>
        </div>
        <div class="">
          <div class=""></div>
        </div>
      </div>
    </section>
    <section class="">
      <div class="row no-wrap scroll q-col-gutter-x-xl">
        <div class="col-auto" v-for="n in 5" :key="n">
          <article>
            <q-avatar size="77px">
              <q-img src="/profile.png" />
            </q-avatar>
            <div class="text-center q-mt-sm">제목</div>
          </article>
        </div>
      </div>
    </section>
    <section class="q-mt-xl">
      <div class="row q-col-gutter-md">
        <div v-for="n in 10" :key="n" class="col-12 col-sm-2 col-md-4 col-lg-3">
          <q-card class="my-card">
            <q-img ratio="1" src="https://cdn.quasar.dev/img/parallax2.jpg">
              <div
                class="absolute-bottom text-subtitle2 text-center full-height flex-center"
              >
                Title
              </div>
            </q-img>
          </q-card>
        </div>
      </div>
    </section>
  </q-page>
</template>

<script setup></script>

<style lang="scss" scoped></style>
