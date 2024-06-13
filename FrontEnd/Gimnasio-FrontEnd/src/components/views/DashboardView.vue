<template>
    <div class="w-full h-full">
        <div class="w-full h-[70%]">
            <Dashboard></Dashboard>
        </div>
        <div class="w-[80%] ml-[3%]">
            <Footer></Footer>
        </div>
    </div>
    
    
</template>
<script>
    import Dashboard from '../../components/Dashboard.vue'
    import Footer from '../Footer.vue';
    
    export default{
        components:
            {
                Dashboard,
                Footer
            }
    }
</script>