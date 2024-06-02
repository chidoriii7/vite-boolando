<script>
export default {
    name: 'AppFooter',
    data() {
        return {
            
        }
    }
}
</script>

<template>
    <footer class="bottom-side white-text">
            <div class="company">
                <span>Boolando s.r.l</span>
                <span>Trovaci anche su</span>
            </div>
            <div class="informations">
                <div>
                    <span>informazioni legali</span>
                    <span>informazioni sulla privacy</span>
                    <span>informazioni Diritto di recesso</span>
                </div>
                <div>
                    <a href="">T</a>
                    <a href="">F</a>
                    <a href="">I</a>
                    <a href="">P</a>
                    <a href="">Y</a>
                </div>
            </div>

        </footer>
</template>

<style>
    .bottom-side {
    margin-top: 30px;
    width: 100%;
    background-color: #1A1A1A;
    padding: 30px;
    
}

.company {
    width: 70%;
    display: flex;
    justify-content: space-between;
    margin: auto;
}

.informations {
    width: 70%;
    display: flex;
    justify-content: space-between;
    margin: auto;
    
}
</style>