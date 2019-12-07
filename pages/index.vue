<template>
  <v-layout>
    <v-flex class="text-center">
      <h2>0daryo</h2>
      <br />
      <div>
        <h2>Background</h2>
        <ul>
          <li>Kyoto University: Faculty of Letter 2014/4~2018/3</li>
          <li>Seattle Consulting.inc: System Engineer 2018/4~2019/3</li>
          <li>Omnis.inc: Server Side Engineer 2019/3~</li>
          <li>ZERO TO ONE: Web Engineer as a Side Job 2019/3~2019/7</li>
        </ul>
      </div>
      <br />
      <div>
        <h2>Languages</h2>
        <ul>
          <li>Java</li>
          <li>javascript</li>
          <li>Golang</li>
        </ul>
      </div>
      <br />
      <div>
        <h2>Other Experiences</h2>
        <ul>
          <li>Spring Boot</li>
          <li>CentOS</li>
          <li>GCP</li>
          <li>Kubernetes</li>
        </ul>
      </div>
      <br />
      <h2>Works</h2>
      <v-dialog width="80%" height="80%">
        <template v-slot:activator="{ on }">
          <v-btn color="red lighten-2" dark v-on="on">ody(インタプリタ)</v-btn>
        </template>

        <v-card>
          <v-card-title class="headline grey lighten-2" primary-title>ody</v-card-title>

          <v-card-text>
            <div>
              <h3>ホスト言語Goのインタプリタ</h3>
              <br />
              <h3>使用技術</h3>
              <ul>
                <li>Go</li>
              </ul>
            </div>
          </v-card-text>

          <v-divider></v-divider>
          <v-card-actions>
            <v-spacer></v-spacer>
            <a href="https://github.com/0daryo/ody" target="_blank">
              Github
              <img height="30px" src="~/assets/images/GitHub-Mark-64px.png" />
            </a>
          </v-card-actions>
        </v-card>
      </v-dialog>
      <br />
      <v-dialog width="80%" height="80%">
        <template v-slot:activator="{ on }">
          <v-btn color="red lighten-2" dark v-on="on">kustomize-lint</v-btn>
        </template>

        <v-card>
          <v-card-title class="headline grey lighten-2" primary-title>kustomize-lint</v-card-title>

          <v-card-text>
            <div>
              <h3>主に業務用のkustomize.yamlをvalidationするツール</h3>
              <br />
              <h3>使用技術</h3>
              <ul>
                <li>Go</li>
              </ul>
            </div>
          </v-card-text>

          <v-divider></v-divider>
          <v-card-actions>
            <v-spacer></v-spacer>
            <a href="https://github.com/0daryo/kustomize-lint" target="_blank">
              Github
              <img height="30px" src="~/assets/images/GitHub-Mark-64px.png" />
            </a>
          </v-card-actions>
        </v-card>
      </v-dialog>
      <br />
      <v-dialog width="80%" height="80%">
        <template v-slot:activator="{ on }">
          <v-btn color="red lighten-2" dark v-on="on">Cinema With</v-btn>
        </template>

        <v-card>
          <v-card-title class="headline grey lighten-2" primary-title>Cinema With</v-card-title>

          <v-card-text>
            <a href="https://cinemawith.app/" target="_blank">
              <img
                src="~/assets/images/cinemawith.png"
                width="40%"
                hight="80%"
                style="float: left;"
              />
            </a>
            <div>
              <h3>上映中の映画を通じたマッチングサービス</h3>
              <br />
              <h3>使用技術</h3>
              <ul>
                <li>vue.js</li>
                <li>Nuxt.js</li>
                <li>firebase auth</li>
                <li>firebase hosting</li>
                <li>realtime database</li>
              </ul>
            </div>
          </v-card-text>

          <v-divider></v-divider>

          <v-card-actions>
            <v-spacer></v-spacer>
            <a href="https://qiita.com/0daryo/items/144f73cd0429afb1e4bb" target="_blank">
              Qiitaで読む
              <img height="30px" src="~/assets/images/qiita-favicon.png" />
            </a>
          </v-card-actions>
        </v-card>
      </v-dialog>
    </v-flex>
  </v-layout>
</template>
<style>
ul {
  list-style: none;
}
</style>