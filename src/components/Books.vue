<template>
  <table class="w-full bg-white border border-gray-300">
    <thead class="bg-gray-100">
      <tr>
        <th class="py-2 px-4 border text-slate-800 text-left">Nama Buku</th>
        <th class="py-2 px-4 border text-slate-800 text-left">Pengarang Buku</th>
        <th class="py-2 px-4 border text-slate-800 text-left">Tahun Rilis</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="py-2 px-4 border text-slate-800">Harry Potter</td>
        <td class="py-2 px-4 border text-slate-800">J.K. Rowling</td>
        <td class="py-2 px-4 border text-slate-800">1997</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">To Kill a Mockingbird</td>
        <td class="py-2 px-4 border text-slate-800">Harper Lee</td>
        <td class="py-2 px-4 border text-slate-800">1960</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">The Great Gatsby</td>
        <td class="py-2 px-4 border text-slate-800">F. Scott Fitzgerald</td>
        <td class="py-2 px-4 border text-slate-800">1925</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">The Catcher in the Rye,</td>
        <td class="py-2 px-4 border text-slate-800">J.D. Salinger</td>
        <td class="py-2 px-4 border text-slate-800">1951</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">Pride and Prejudice</td>
        <td class="py-2 px-4 border text-slate-800">Jane Austen,</td>
        <td class="py-2 px-4 border text-slate-800">1813</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">The Hobbit</td>
        <td class="py-2 px-4 border text-slate-800">J.R.R. Tolkien</td>
        <td class="py-2 px-4 border text-slate-800">1937</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">The Da Vinci Code</td>
        <td class="py-2 px-4 border text-slate-800">Dan Brown</td>
        <td class="py-2 px-4 border text-slate-800">2003</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">The Shining</td>
        <td class="py-2 px-4 border text-slate-800">Stephen King</td>
        <td class="py-2 px-4 border text-slate-800">1977</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">The Lord of the Rings</td>
        <td class="py-2 px-4 border text-slate-800">J.R.R. Tolkien</td>
        <td class="py-2 px-4 border text-slate-800">1955</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">Brave New World</td>
        <td class="py-2 px-4 border text-slate-800">Aldous Huxley</td>
        <td class="py-2 px-4 border text-slate-800">1932</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">The Alchemist</td>
        <td class="py-2 px-4 border text-slate-800">Paulo Coelho</td>
        <td class="py-2 px-4 border text-slate-800">1988</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">Gone with the Wind</td>
        <td class="py-2 px-4 border text-slate-800">Margaret Mitchell</td>
        <td class="py-2 px-4 border text-slate-800">1936</td>
      </tr>
      <tr>
        <td class="py-2 px-4 border text-slate-800">The Hunger Games</td>
        <td class="py-2 px-4 border text-slate-800">Suzanne Collins</td>
        <td class="py-2 px-4 border text-slate-800">2008</td>
      </tr>
    </tbody>
  </table>
</template>

<script lang="ts">
import { defineComponent } from "vue";
export default defineComponent({
  name: "Greet",
});
</script>
