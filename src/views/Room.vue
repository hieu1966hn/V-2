<template>
  <section>
    <table class="table">
      <thead>
        <tr>
          <th scope="col">#</th>
          <th scope="col">Phòng</th>
          <th scope="col">Số lượng</th>
          <th scope="col">Khác</th>
          <th scope="col"></th>
        </tr>
      </thead>
      <tbody>
        <tr v-bind:key="item.id" v-for="(item, index) in rooms">
          <th>{{ index + 1 }}</th>
          <td>{{ item.room }}</td>
          <td>{{ item.population + "/" + item.capacity }}</td>
          <td></td>
          <td>
            <router-link to="/person" role="button" class="btn btn-info">
              Xem
            </router-link>
          </td>
        </tr>
      </tbody>
    </table>
  </section>
</template>

<script>
export default {
  name: "Room",
  data: function () {
    return {
      rooms: [
        {
          room: 19,
          population: 6,
          capacity: 20,
        },
        {
          room: 9,
          population: 18,
          capacity: 20,
        },
        {
          room: 39,
          population: 3,
          capacity: 20,
        },
        {
          room: 94,
          population: 16,
          capacity: 20,
        },
        {
          room: 53,
          population: 13,
          capacity: 20,
        },
        {
          room: 57,
          population: 15,
          capacity: 20,
        },
        {
          room: 15,
          population: 19,
          capacity: 20,
        },
        {
          room: 7,
          population: 13,
          capacity: 20,
        },
        {
          room: 19,
          population: 4,
          capacity: 20,
        },
        {
          room: 56,
          population: 8,
          capacity: 20,
        },
      ],
    };
  },
  components: {},
};
</script>
