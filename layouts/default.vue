<template>
  <div>
    <nuxt />
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.button--linkedin {
  display: inline-block;
  border-radius: 6px;
  border: 1px solid #2867b2;
  color: #2867b2;
  text-decoration: none;
  padding: 10px 15px;
}

.button--linkedin:hover {
  color: #fff;
  background-color: #2867b2;
}

.button--github {
  display: inline-block;
  border-radius: 6px;
  border: 1px solid #211f1f;
  color: #211f1f;
  text-decoration: none;
  padding: 10px 15px;
  margin-left: 5px;
}

.button--github:hover {
  color: #fff;
  background-color: #211f1f;
}

.button--instagram {
  display: inline-block;
  border-radius: 6px;
  border: 1px solid #c13584;
  color: #c13584;
  text-decoration: none;
  padding: 10px 15px;
  margin-left: 5px;
}

.button--instagram:hover {
  color: #fff;
  background-color: #c13584;
}
</style>
