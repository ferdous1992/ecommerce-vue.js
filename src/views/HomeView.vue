<template>
    <div>
        <HeroArea/>
        <FeaturedCategory/>
        <TrendingProduct/>
        <BannerSection/>
        <SpecialOffer/>
        <HomeProduct/>
        <BrandSection/>
        <BlogSection/>
        <ShippingSection/>
    </div>
</template>

<script>
    import HeroArea from "@/components/home/HeroArea";
    import FeaturedCategory from "@/components/home/FeaturedCategory";
    import TrendingProduct from "@/components/home/TrendingProduct";
    import BannerSection from "@/components/home/BannerSection";
    import SpecialOffer from "@/components/home/SpecialOffer";
    import HomeProduct from "@/components/home/HomeProduct";
    import BrandSection from "@/components/home/BrandSection";
    import BlogSection from "@/components/home/BlogSection";
    import ShippingSection from "@/components/home/ShippingSection";
    export default {
      name: 'HomeView',
      components: {HeroArea,FeaturedCategory,TrendingProduct,BannerSection,SpecialOffer,HomeProduct,BrandSection,BlogSection,ShippingSection},
      created() {
          document.title = "Home Page"
      }
    }
</script>
