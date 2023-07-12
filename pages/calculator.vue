<template>
    <div class="main-container">
        <h1>Hitung Kebutuhan Kalorimu.</h1>
        <form>
            <div>
                <label>
                    <div>
                        <input type="number" placeholder="No. Handphone" v-model="phoneNumber" />
                    </div>
                </label>
                <label>
                    <div>
                        <input type="text" placeholder="city" v-model="phoneNumber" />
                    </div>
                </label>
            </div>
        </form>
    </div>
</template>

<script setup lang="ts">
useHead({
    title: 'Higlo | Hitung kalorimu'
})

const phoneNumber = ref('')
const city = ref('')

const weight = ref('')
const height = ref('')
const activity = ref('')

</script>