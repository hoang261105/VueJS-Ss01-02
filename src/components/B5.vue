<template>
  <div>
    <h2>Thông tin cá nhân</h2>
    <ul>
      <li>Họ và tên: {{ name }}</li>
      <li>Giới tính: {{ gender }}</li>
      <li>Ngày sinh: {{ birthday }}</li>
      <li>Email: {{ email }}</li>
      <li>Địa chỉ: {{ address }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: "Nguyễn Văn A",
      gender: "Nam",
      birthday: "12/02/2003",
      email: "nguyenvana@gmail.com",
      address: "Hà Nội",
    };
  },
};
</script>

<style></style>
