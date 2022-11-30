# README

This is React tutorial dir

## Install Vite

<https://ja.vitejs.dev/guide/#%E6%9C%80%E5%88%9D%E3%81%AE-vite-%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%82%92%E7%94%9F%E6%88%90%E3%81%99%E3%82%8B>

1. `yarn create vite`
   1. プロジェクト名設定
   2. `React`
   3. `TypeScript`
2. `yarn install`
3. `yarn dev` でサーバーが立ち上がる

## Start React tutorial

<https://ja.reactjs.org/tutorial/tutorial.html>

1. `App.tsx`を`Game.tsx`にリネーム
2. [スターターコード](https://codepen.io/gaearon/pen/oWWQNa?editors=0010)のJSを`Game.tsx`にコピペ
   1. スターターコード58行目以下は削除
   2. `Game.tsx`1行目に`import React from 'react'`を追加
   3. `Game.tsx`最終行に`export default Game`を追加
3. `App.css`を削除
4. スターターコードのCSSを`index.css`にコピペ
5. サーバーが立ち上がっていると画面にマスが描画される
