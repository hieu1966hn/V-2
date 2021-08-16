<template>
  <section>
    <table class="table">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">Họ và tên</th>
          <th scope="col">Số phòng</th>
          <th scope="col">Số điện thoại</th>
          <th scope="col">Ngày bắt đầu cách ly</th>
          <th scope="col"></th>
        </tr>
      </thead>
      <tbody>
        <tr v-bind:key="item.id" v-for="item in persons">
          <th>{{ item.id }}</th>
          <td>{{ item.name }}</td>
          <td>{{ item.room }}</td>
          <td>{{ item.phoneNumber }}</td>
          <td>{{ item.startDate }}</td>
          <td>
            <router-link to="/status" role="button" class="btn btn-info me-2">Xem</router-link>
            <button type="button" class="btn btn-success">Sửa</button>
          </td>
        </tr>
      </tbody>
    </table>
  </section>
  <section></section>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Person",
  data: function () {
    return {
      persons: [
        {
          id: 1,
          name: "Dominica Shilstone",
          room: 91,
          phoneNumber: "713-520-4333",
          startDate: "7/19/2021",
        },
        {
          id: 2,
          name: "Banky Kolakowski",
          room: 50,
          phoneNumber: "222-293-3258",
          startDate: "1/26/2021",
        },
        {
          id: 3,
          name: "Oona Beames",
          room: 60,
          phoneNumber: "197-180-2526",
          startDate: "9/8/2020",
        },
        {
          id: 4,
          name: "Penni Suero",
          room: 94,
          phoneNumber: "102-705-2192",
          startDate: "1/23/2021",
        },
        {
          id: 5,
          name: "Gabriele Doelle",
          room: 58,
          phoneNumber: "870-287-3024",
          startDate: "12/24/2020",
        },
      ],
    };
  },
  components: {
    HelloWorld,
  },
};
</script>
