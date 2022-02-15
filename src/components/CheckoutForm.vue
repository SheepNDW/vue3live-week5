<template>
  <form ref="form" class="col-md-6">
    <div class="mb-3">
      <label for="email" class="form-label">Email</label>
      <input
        id="email"
        name="email"
        type="email"
        class="form-control"
        placeholder="請輸入 Email"
      />
      <span name="email" class="invalid-feedback"></span>
    </div>

    <div class="mb-3">
      <label for="name" class="form-label">收件人姓名</label>
      <input
        id="name"
        name="姓名"
        type="text"
        class="form-control"
        placeholder="請輸入姓名"
      />
      <span name="姓名" class="invalid-feedback"></span>
    </div>

    <div class="mb-3">
      <label for="tel" class="form-label">收件人電話</label>
      <input
        id="tel"
        name="電話"
        type="text"
        class="form-control"
        placeholder="請輸入電話"
      />
      <span name="電話" class="invalid-feedback"></span>
    </div>

    <div class="mb-3">
      <label for="address" class="form-label">收件人地址</label>
      <input
        id="address"
        name="地址"
        type="text"
        class="form-control"
        placeholder="請輸入地址"
      />
      <span name="地址" class="invalid-feedback"></span>
    </div>

    <div class="mb-3">
      <label for="message" class="form-label">留言</label>
      <textarea
        id="message"
        class="form-control"
        cols="30"
        rows="10"
      ></textarea>
    </div>
    <div class="text-end">
      <button type="submit" class="btn btn-danger">送出訂單</button>
    </div>
  </form>
</template>

<script>
export default {
  name: 'CheckoutForm',
};
</script>

<style lang="scss" scoped></style>
