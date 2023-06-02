<script setup lang="ts">
import LeafRow from '../components/LeafRow.vue'
</script>
<template>
  <p class="title">Profile.</p>

  <div class="tree-container">
    <LeafRow title="2013.4 ~ 2017.3" sentence=" 大学で電子情報工学を学ぶ。"></LeafRow>
    <br>
    <LeafRow title="2017.7 ~ 2019.9" sentence=" 株式会社アルカディアプラス入社"></LeafRow>
    <LeafRow title="" sentence="大手住宅設備メーカーにてシステム開発に従事" substance="見積もり発注システムの開発・保守" language="[使用言語] Java, JavaScript" db="[DB] SQL Server"  versioncontrol="[バージョン管理] SVN"></LeafRow>
    <br>
    <LeafRow title="2019.10 ~ 2020.5" sentence="大手SIerにてシステム開発に従事" substance="ログ分析ツールの改修・対話型サービスにおけるアプリケーション開発" language="[使用言語] Node.js" framework="[フレームワーク] Express" versioncontrol="[バージョン管理] Git" other="[その他] Docker, ElasticSearch, Kibana, ansible"></LeafRow>
    <br>
    <LeafRow title="2020.9 ~ " sentence="株式会社エラン入社" ></LeafRow>
    <br>
    <LeafRow title="" sentence="情報システム部にてシステム開発・保守に従事" language="[使用言語] PHP, JavaScript, C#" framework="[フレームワーク] Laravel, Vue" db="[DB] PostgreSQL" versioncontrol="[バージョン管理] Git" other="[その他] AWS, Docker, OpenSearch"></LeafRow>
  </div>
</template>
