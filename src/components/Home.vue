<template>
    <div>this is home</div>
    <TestComp :count="count" :testObj="post" />
    <button @click="count++">click me</button>
    <BigBlock>
        <template v-slot:third> <p>world</p></template>
        <template v-slot:first> <p>hallooo</p></template>
        <p>not you</p>
    </BigBlock>
</template>
<script>
import TestComp from './TestComp.vue';
import BigBlock from './BigBlock.vue';

export default {
    components: {
        TestComp,
        BigBlock,
    },
    data() {
        return {
            count: 0,
            post: [
                {
                    id: 'here is id',
                    name: 'here is name',
                },
                {
                    id: 'hasdasdasd',
                    name: 'xxxx',
                },
            ],
        };
    },
};
</script>
<style lang=""></style>
