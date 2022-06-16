<template lang="">
    <div>{{ count }}</div>
    <div>
        <div v-for="(singleObj, index) in testObj" :key="index">
            <div>{{ index }}</div>
            <div>{{ singleObj.id + ' - ' + singleObj.name }}</div>
        </div>
    </div>
</template>
<script>
export default {
    props: { count: Number, testObj: Object },
};
</script>
<style lang=""></style>
