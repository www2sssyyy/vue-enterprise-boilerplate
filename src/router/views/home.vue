<script>
import appConfig from '@src/app.config';
import Layout from '@layouts/main';
import data from './data';

export default {
  page: {
    title: 'Home',
    meta: [{ name: 'description', content: appConfig.description }],
  },
  components: { Layout },
  data() {
    return {
      data,
    };
  },
};
</script>

<template>
  <Layout>
    <h1>Home Page</h1>
    <img src="@assets/images/logo.png" alt="Logo" scd="dsf" sdsd="df" dfsdf="ff">
  </Layout>
</template>
