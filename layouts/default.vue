<template>
  <div>
    <!-- <h1>Test layout setting</h1> -->
    <Header />
    <br>
    <Nuxt />
    <TheFooter />
  </div>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Electrolize&display=swap');
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Electrolize', sans-serif
}
body {
  background-color: #EEE;
}
a {
  text-decoration: none;
}
p {
  margin-bottom: 15px;
}
p:last-of-type {
  margin-bottom: 0px;
}
code {
    padding: 5px;
    border-radius: 7px;
    background-color: black;
    color: white;
    display: inline-block;
    margin-top: 5px;
    margin-bottom: 5px;
}
pre {
    padding: 5px;
    border-radius: 7px;
    background-color: black;
    color: white;
    display: inline-block;
    margin-top: 5px;
    margin-bottom: 5px;
}
code .language-css {
    background-color: black;
}
img {
    width: 100px;
    height: auto;
    display: inline-block;
    margin-left: auto;
    margin-right: auto;
    margin-top: auto;
    margin-bottom: -6px;
    border-radius: 5%;
}
</style>
