<template lang="">
    <div>
        <div>{{ count }}</div>
        <button @click="count++">click here</button>
    </div>
</template>
<script>
export default {
    data() {
        return { count: 0 };
    },
};
</script>
<style lang=""></style>
