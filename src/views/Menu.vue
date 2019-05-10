<template>
    <div>
        <home-plans></home-plans>
        <meal-recipes></meal-recipes>
        <contact-details></contact-details>
    </div>
</template>

<script>
import HomePlans from '@/components/HomePlans';
import MealRecipes from '@/components/MealRecipes';
import ContactDetails from '@/components/ContactDetails';

export default {
    name: 'Menu',
    components: {
        HomePlans,
        MealRecipes,
        ContactDetails
    }
};
</script>

<style scoped>
</style>