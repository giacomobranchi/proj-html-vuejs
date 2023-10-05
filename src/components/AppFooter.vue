<script>
export default {
    data() {
        return {
            name: 'AppFooter'
        }
    }
}
</script>

<template>
    <footer>
        <div class="container">
            <div class="row">
                <div class="col-2">
                    <ul>
                        <li>GET STARTED</li>
                        <li>Resources</li>
                        <li>Tutorials</li>
                        <li>Esamples</li>
                        <li>Docs</li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul>
                        <li>ABOUT</li>
                        <li>Stories</li>
                        <li>Community</li>
                        <li>Blog</li>
                        <li>Brand Assets</li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul>
                        <li>FEATURES</li>
                        <li>Overwiev</li>
                        <li>Design</li>
                        <li>Code</li>
                        <li>Collaborate</li>
                    </ul>
                </div>
                <div class="col-2">
                    <ul>
                        <li>QUICK LINKS</li>
                        <li>Stories</li>
                        <li>Community</li>
                        <li>Blog</li>
                        <li>Brand Assets</li>
                    </ul>
                </div>
                <div class="col-3">
                    <div>SUBSCRIBE TO NEWSLETTER</div>
                    <input class="w100" type="text" name="email" id="" placeholder="Email">
                    <button type="button" class="btn btn_bg text-white w-100">SUBSCRIBE</button>
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

    & button {

        background-color: #555353;
    }
}
</style>