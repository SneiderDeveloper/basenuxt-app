<template>    
    <div class="tw-flex tw-gap-16 tw-flex-col tw-items-center">
        <BreadCrumbs />
        <div class="tw-flex tw-gap-[30px] tw-w-[1680px]">
            <div>
                <categories />
            </div>
            <div>		
                <div>
                    <img 
                        class="tw-h-auto tw-max-w-full tw-rounded"
                        alt="Category"
                        src=".././assets/img/category.png" 
                    />
                </div>
                <div class="tw-pt-5 tw-mt-2.5">
                    <span class="tw-text-4xl tw-font-semibold">Hosting Cpanel (PHP)</span>
                    <p class="tw-text-base tw-mt-3.5">
                        CPanel Última versión con Cloudlinux, Softaculous, Imunify360 y JetBackup. Máxima Velocidad con Litespeed Incluido. Ahora con PHP 8!   
                    </p>
                </div>
                <hr  class="tw-my-6" />
                <div class="">
                    <ProductsComponent/>        
                </div>
            </div>
        </div>
        <Footer />
    </div>

</template>
<script setup lang="ts">
import ProductsComponent from '../components/products';
import categories from '../components/categories';
import BreadCrumbs from '../components/breadcrumbs';
import Footer from '../components/footer';

const router = ref(useRouter())
</script>