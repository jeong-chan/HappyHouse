<template>
  <b-container class="bv-example-row mt-3">
    <b-row>
      <b-col>
        <b-alert show><h3>글수정</h3></b-alert>
      </b-col>
    </b-row>
    <qna-input-item type="modify" />
  </b-container>
</template>

<script>
import QnaInputItem from "@/components/Qna/item/QnaInputItem.vue";

export default {
  name: "qnamodify",
  components: {
    QnaInputItem,
  },
};
</script>

<style></style>
