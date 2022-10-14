<template>
  <section>
    <h2>My Friends</h2>
    <ul>
      <li></li>
    </ul>
  </section>
</template>

<script>
export default {
  data() {
    return {
      friends: [
        {
          id: "jenny",
          name: "Jenny",
          phone: "012 3456 7890",
          email: "jenny@localhost.com",
        },
        {
          id: "john",
          name: "John Wick",
          phone: "098 7654 3210",
          email: "wick@localhost.com",
        },
      ],
    };
  },
};
</script>