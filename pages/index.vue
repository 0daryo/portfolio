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
        <a href="https://0daryo.github.io/job-description/" target="_blank">Detail Job Description</a>
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
      <br />
      <v-dialog width="80%" height="80%">
        <template v-slot:activator="{ on }">
          <v-btn color="red lighten-2" dark v-on="on">kustomize-lint</v-btn>
        </template>

        <v-card>
          <v-card-title class="headline grey lighten-2" primary-title>kustomize-lint</v-card-title>

          <v-card-text>
            <div>
              <h3>主に業務用のkustomization.yamlをvalidationするツール</h3>
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
    </v-flex>
  </v-layout>
</template>
<style>
ul {
  list-style: none;
}
a {
  color: skyblue;
  font-size: 2em; /*文字サイズ2倍*/
  font-weight: bold;
}
</style>