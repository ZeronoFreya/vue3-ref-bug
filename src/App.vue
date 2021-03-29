<template>
  <div>demo</div>
</template>

<script setup>
ref: demo = "";

const temp1 = {
  demo,
};
console.log(temp1);   // output: {demo: ""}

const fun = () => {
  const temp2 = {
    demo,
  };
  console.log(temp2);  // output: {demo: RefImpl}
};
fun();
</script>