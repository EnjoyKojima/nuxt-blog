<script setup lang="ts">
</script>

<template>
  <div>
    <header class="bg-gray-800 text-white">
      <h1>
        <a href="/">
          Kojima
        </a>
      </h1>
      <nav>
        <ul>
          <li><a href="/">ホーム</a></li>
          <li><a href="/about">アバウト</a></li>
          <li><a href="/contact">コンタクト</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section>
        <h2>最新の記事</h2>
        <article>
          <h3>記事タイトル1</h3>
          <p>この記事の概要...</p>
          <a href="/post/1">続きを読む</a>
        </article>
        <article>
          <h3>記事タイトル2</h3>
          <p>この記事の概要...</p>
          <a href="/post/2">続きを読む</a>
        </article>
        <Button>ボタン</Button>
      </section>
    </main>
    <footer>
        <p>&copy; 2023 私のウェブサイト</p>
    </footer>
  </div>
</template>
