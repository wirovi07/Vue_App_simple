<template>
    <div :style="msg.style" class="msg-cont">
        <p>{{ msg.value }}</p>
    </div>
</template>

<script>

    export default{
        name: "MsgComp",
        props: {
            msg:{
                type: Object,
                required: true
            }
        }
    }

</script>

<style scoped>

.msg-cont{
    max-width: 251px;
    padding: 2em;
    margin: auto;
    color: white;
}
</style>