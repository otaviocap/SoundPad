<template>
  <Container>
      <section class="middle">
        <Row wrap>
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
        </Row>
      </section>
      <section class="right">
        <Row wrap>
          <Card />
          <Card />
          <Card />
          <Card />
          <Card />
        </Row>
      </section>
  </Container>
</template>

<script setup lang="ts">
import Column from './components/ui-foundation/Column.vue';
import Container from './components/ui-foundation/Container.vue';
import Row from './components/ui-foundation/Row.vue';
import Card from './components/widgets/Card.vue';

</script>

<style scoped lang="scss">

section {
  height: 100%;
  overflow: scroll;
}

.middle {
  grid-area: middle;
}

.right {
  grid-area: right;
}
</style>
