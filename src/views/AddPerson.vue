<template>
  <section class="text-start">
    <div class="mb-3">
      <label for="exampleFormControlInput1" class="form-label">Tên</label>
      <input
        type="text"
        class="form-control"
        id="exampleFormControlInput1"
        placeholder=""
      />
    </div>
    <div class="mb-3">
      <label for="exampleFormControlInput1" class="form-label">Phòng</label>
      <input
        type="text"
        class="form-control"
        id="exampleFormControlInput1"
        placeholder=""
      />
    </div>
    <div class="mb-3">
      <label for="exampleFormControlInput1" class="form-label">Số điện thoại</label>
      <input
        type="text"
        class="form-control"
        id="exampleFormControlInput1"
        placeholder=""
      />
    </div>
    <div class="mb-3">
      <label for="exampleFormControlTextarea1" class="form-label"
        >Thông tin khác</label
      >
      <textarea
        class="form-control"
        id="exampleFormControlTextarea1"
        rows="3"
      ></textarea>
    </div>
    <div class="d-flex">
        <router-link active-class="active" class="btn btn-success ms-auto" to="/person">
          Thêm
        </router-link>
    </div>
  </section>
</template>

<script>
export default {
  name: "AddPerson",
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
  components: {},
};
</script>
