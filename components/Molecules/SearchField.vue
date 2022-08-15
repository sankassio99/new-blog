<template>
  <div class="flex p-2 bg-gray-50 rounded-xl">
    <text-field
      list="category"
      icon="search"
      placeholder="Search for blogs"
    ></text-field>
    <filter-button></filter-button>
    <datalist id="category">
      <option value="Tech"></option>
      <option value="Personal Development"></option>
      <option value="Vue"></option>
      <option value="JavaScript"></option>
      <option value="Carrer"></option>
    </datalist>
  </div>
</template>

<script>
import FilterButton from '../Atoms/FilterButton.vue'
import TextField from '../Atoms/TextField.vue'
export default {
  components: { TextField, FilterButton },
}
</script>

<style></style>
