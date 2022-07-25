<script setup>
// export default{
//     data(){
//         return{
//             currentYear: new Date().getFullYear(),
//         };
//     }
// };
let currentYear = new Date().getFullYear();
</script>

<template>
<div class="mt-2 py-2 bg-slate-600 text-white">
    <ul class="items-center text-center">
        <li>ManticLabs Web Solution Pvt Ltd.</li>
        <li >Copyright &copy; {{currentYear}} All rights Reserved.</li>
    </ul>
</div>
</template>