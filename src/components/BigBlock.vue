<template lang="">
    <div>
        1
        <slot name="first"></slot>
    </div>
    <div>
        2
        <slot></slot>
    </div>
    <div>
        3
        <slot name="third"></slot>
    </div>
</template>
<script>
export default { name: 'BigBlock' };
</script>
<style lang=""></style>
