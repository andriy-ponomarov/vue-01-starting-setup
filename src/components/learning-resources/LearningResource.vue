<template>
  <li>
    <div>
      <hearer>
        <h3>
          {{ title }}
        </h3>
        <button>Delete</button>
      </hearer>
    </div>
    <p>{{ description }}</p>
    <nav>
      <a :href="link" target="_blank">View Resource</a>
    </nav>
  </li>
</template>

<script>
export default {
  props: ['title', 'description', 'link'],
};
</script>
