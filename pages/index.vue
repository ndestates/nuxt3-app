<template><div>
<div>This is our main page</div>
<counter />
<div>Mouse position: x: {{ x }} y: {{ y }}</div>
</div>
</template>
<script setup>
const { x, y,} = useMouse()
</script>