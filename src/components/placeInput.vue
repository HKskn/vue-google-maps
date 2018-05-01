<template>
    <label>
        <span v-text="label"></span>
        <input type="text" :placeholder="placeholder" :class="className"
          ref="input"/>
    </label>
</template>

<script>
	export default (function (x) { return x.default || x })(require('./placeInputImpl.js'))
</script>
