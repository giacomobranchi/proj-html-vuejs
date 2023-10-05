<script>
export default {
    data() {
        return {
            name: 'AppFooter',
            bgBtn: 'background-color: #555353; color: white;',
            footerLinks: [{
                getStarted: {
                    title: 'GET STARTED',
                    voice: ['Resources', 'Tutorials', 'Examples', 'Docs']
                },
                about: {
                    title: 'ABOUT',
                    voice: ['Stories', 'Community', 'Blog', 'Brand Assets']

                },
                features: {
                    title: 'FEATURES',
                    voice: ['Overwiev', 'Design', 'Code', 'Collaborate']

                },
                quickLinks: {
                    title: 'QUICK LINKS',
                    voice: ['Stories', 'Community', 'Blog', 'Brand Assets']
                },
            }]
        }
    },
    methods: {
        btnHover() {
            this.bgBtn = 'color: #bf1d2e !important; background-color: white !important;'
        },
        btnLeave() {
            this.bgBtn = 'background-color: #555353; color: white;'
        }

    }
}
</script>

<template>
    <footer>
        <div class="container">
            <div class="row">
                <div v-for="link in footerLinks" class="col-2">
                    <ul>
                        <li>{{ link.getStarted.title }}</li>
                        <li v-for="voice in link.getStarted.voice">{{ voice }}</li>

                    </ul>
                </div>
                <div v-for="link in footerLinks" class="col-2">
                    <ul>
                        <li>{{ link.about.title }}</li>
                        <li v-for="voice in link.about.voice">{{ voice }}</li>

                    </ul>
                </div>
                <div v-for="link in footerLinks" class="col-2">
                    <ul>
                        <li>{{ link.features.title }}</li>
                        <li v-for="voice in link.features.voice">{{ voice }}</li>

                    </ul>
                </div>
                <div v-for="link in footerLinks" class="col-2">
                    <ul>
                        <li>{{ link.quickLinks.title }}</li>
                        <li v-for="voice in link.quickLinks.voice">{{ voice }}</li>

                    </ul>
                </div>
                <div class="col-3">
                    <div>SUBSCRIBE TO NEWSLETTER</div>
                    <input class="w100" type="text" name="email" id="" placeholder="Email">
                    <button @mouseover="btnHover" @mouseleave="btnLeave" type="button" class="btn btn_bg w-100"
                        :style="bgBtn">SUBSCRIBE</button>
                </div>
            </div>
            <hr>
            <div class="row justify-content-between align-items-center">
                <div class="col-2">
                    <img src="../assets/img/anime-whitelogo-300x89.png" alt="">
                </div>
                <div class="col-3">
                    <small>© Anime Tech, Theme by HasnainDEV</small>
                </div>
            </div>
        </div>
    </footer>
</template>



<style lang="scss" scoped>
footer {
    padding: 2rem 0;
    background-color: #bf1d2e;
    box-shadow: inset 0px 3px 5px #000000;
    color: white;

    & ul {
        list-style: none;

    }

    & input {
        width: 100%;
        margin: 1rem 0;
    }

    & li {
        font-weight: 600;

        &:hover {
            color: #555353;
        }
    }

}
</style>