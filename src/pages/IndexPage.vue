<template>
  <q-page class="flex quasar-landing-page">
    <div>
      <h1>Market options order flow</h1>
      <p>
        Providing market option order flow and analytics to make your best
        trades.
      </p>
      <button>Get Started</button>
    </div>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({
  name: "IndexPage",
});
</script>

<style lang="scss" scoped>
.quasar-landing-page {
  background-image: url("../assets/quasar-bg.jpg");
  background-size: cover;
  background-position: 50%;
  padding: 0 50px;
  align-items: center;

  div {
    max-width: 500px;
    color: white;

    h1 {
      font-size: 56px;
      margin: 0;
      line-height: 64px;
      font-weight: bold;
    }

    p {
      font-size: 18px;
      margin: 10px 0;
    }

    button {
      width: 158px;
      height: 54px;
      border-radius: 4px;
      background: white;
      outline: none;
      border: none;
      color: black;
      font-weight: 600;
      font-size: 16px;
      margin-top: 10px;
      padding-top: 5px;
      cursor: pointer;

      &:hover {
        opacity: 0.7;
      }
    }
  }

  @media (max-width: 960px) {
    padding: 0 25px;

    div {
      max-width: 400px;
      h1 {
        font-size: 46px;
        line-height: 50px;
      }
    }
  }

  @media (max-width: 600px) {
    div {
      max-width: 250px;
      h1 {
        font-size: 34px;
        line-height: 40px;
      }
      p {
        font-size: 16px;
      }
    }
  }

  @media (max-width: 525px) {
    align-items: inherit;
    padding-top: 55px;

    div {
      max-width: inherit;

      h1 {
        font-size: 20px;
      }
      p {
        font-weight: bold;
      }
    }
  }
}
</style>
