
<template>
    <div class="main-container">

        <Header />
        
        <Breadcrumbs :items="breadcrumbNavigation" breadcrumbTitle="Contact Us" />

        <ContactUsFour />

        <CtaOne />

        <Footer />

        <OffCanvasMobileMenu />

    </div>
</template>

<script>
    import Header from '@/components/Header';
    import Breadcrumbs from '@/components/Breadcrumbs';
    import ContactUsFour from '@/components/sections/ContactUsFour';
    import CtaOne from '@/components/CtaOne';
    import Footer from '@/components/Footer';
    import OffCanvasMobileMenu from '@/components/OffCanvasMobileMenu';

    export default {
        name: 'contact',
        components: {
            Header,
            Breadcrumbs,
            ContactUsFour,
            CtaOne,
            Footer,
            OffCanvasMobileMenu
        },
        head() {
            return {
                title: 'Contact Us'
            }
        },
        data () {
            return {
                breadcrumbNavigation: [
                    {
                        text: 'Home',
                        to: "/"
                    },
                    {
                        text: 'Contact Us',
                        active: true
                    }
                ]
            }
        }
    };
</script>