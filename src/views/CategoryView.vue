<template>
    <div class="category-view">
        <PageTitleSection/>
        <section class="product-grids section">
            <div class="container">
                <div class="row">
                    <div class="col-lg-3 col-12">
                        <LeftSection/>
                    </div>
                    <div class="col-lg-9 col-12">
                        <RightSection/>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
    import PageTitleSection from "@/components/category/PageTitleSection";
    import LeftSection from "@/components/category/LeftSection";
    import RightSection from "@/components/category/RightSection";

    export default {
        name: "CategoryView",
        components:{PageTitleSection, LeftSection,RightSection},
        data() {
            return {
            }
        },
        created() {
            document.title = "Product Category Page";
        }
    }
</script>

<style scoped>

</style>