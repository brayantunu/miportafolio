<template>
    <div>
        <profile/>
    </div>
    <div>
        <education/>
    </div>
   
</template>
<script>
import Education from "@/components/education.vue"
import Profile from '@/components/profile.vue'

export default{
    name:'portafolio-vue',
    components:{
        Education, Profile
    }
}

       

       </script>