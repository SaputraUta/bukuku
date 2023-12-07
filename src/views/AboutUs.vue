<template>
  <div class="mt-10">
    <h2 class="text-3xl font-bold text-slate-800">About Us</h2>

    <section class="mt-5">
      <p>
        Welcome to Bukuku, your go-to destination for all things books! Our
        passion for literature drives us to create an online platform that
        connects readers, authors, and publishers.
      </p>
      <p>
        At Bukuku, we believe in the power of storytelling to inspire, educate,
        and entertain. Our mission is to provide a seamless and enjoyable
        experience for book enthusiasts around the world.
      </p>
    </section>

    <section class="mt-5">
      <h3 class="text-2xl font-bold text-slate-800">Our Values</h3>
      <ul class="list-disc pl-5">
        <li>
          <strong>Passion:</strong> We are passionate about books and their
          impact on individuals and society.
        </li>
        <li>
          <strong>Diversity:</strong> We celebrate the diverse voices and
          stories that make up the world of literature.
        </li>
        <li>
          <strong>Community:</strong> We strive to build a vibrant and
          supportive community of readers, authors, and publishers.
        </li>
        <li>
          <strong>Innovation:</strong> We embrace innovation to enhance the way
          people discover, share, and experience books.
        </li>
      </ul>
    </section>

    <section class="mt-5">
      <h3 class="text-2xl font-bold text-slate-800">Contact Us</h3>
      <p>
        We'd love to hear from you! If you have any questions, feedback, or just
        want to say hello, feel free to
        <router-link to="/contact-us" class="text-blue-500 hover:underline">contact us</router-link>.
      </p>
    </section>
  </div>
</template>
<script lang="ts">
export default {
  name: "About",
};
</script>
