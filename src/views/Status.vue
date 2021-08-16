<template>
  <article class="text-start">
    <h1 class="fw-bold">Thông tin người cách ly</h1>
    <hr />
    <h3>Thông tin cá nhân</h3>
    <p>Họ và tên: Lonny Harefoot</p>
    <p>Ngày sinh: 05/03/1995</p>
    <p>Giới tính: Nam</p>
    <p>Số điện thoại: 0123456342</p>
    <p>email: fakeemail@gmail.com</p>
    <h3>Tình trạng sức khỏe</h3>
    
    <table class="table">
      <thead>
        <tr>
          <th scope="col">Ngày</th>
          <th scope="col">Ho</th>
          <th scope="col">Sốt</th>
          <th scope="col">Đau đầu</th>
          <th scope="col">Đau rát họng</th>
          <th scope="col">Sổ mũi</th>
          <th scope="col">Khó thở</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>01/02/2021</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
        </tr>
        <tr>
          <td>02/02/2021</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
        </tr>
        <tr>
          <td>03/02/2021</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
        </tr>
        <tr>
          <td>04/02/2021</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
          <td>Không</td>
        </tr>
      </tbody>
    </table>
  </article>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Status",
  data: function () {
    return {
    };
  },
  components: {
    HelloWorld,
  },
};
</script>
