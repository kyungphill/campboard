<template>
  <div>
    <tool-bar>
      <template v-slot:main>
        <PointTable />
      </template>
    </tool-bar>
  </div>
</template>

<script>
import ToolBar from "../components/ToolBar";
import PointTable from "../components/point-board/PointTable.vue";
export default {
  components: { ToolBar, PointTable }
};
</script>

<style>
</style>