<template>
    <div>
        <div id="familysite">
        </div>
        <div id="background">
            <div class="container">
                <div id="header-title">
                    <img id="header-icon" src="~static/image/lolchessicon.png"/>
                    <h1>LOL Chess clone coding</h1>    
                </div>
                <div id="direct-link">
                    <ul>
                        <li>가이드</li>
                        <li>추천메타</li>
                        <li>아이템</li>
                        <li>배치율</li>
                        <li>시뮬레이터</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : "header",
    data(){
        return {
            
        }
    }
}
</script>

<style>
#familysite{
    height: 40px;
    background-color: #3a3f4c;
}
#familysite>li{
    height: 40px;
}
#background{
    background-image: url("~static/image/background-banner.png");
    background-position-x: right;
    height: 200px;
}
#header-title{
    padding-top:60px;
    height: 160px;
}

#header-title > h1{
    height: 160px;
}
#direct-link{
    height: 40px;
}
#header-icon{
    float: left;
    width: 3rem;
}
h1{
    color: white;
}
ul{
    margin: 0;
    padding: 0;
}
li{
    display: inline;
    margin-right: 10px;
    color: #d6d6d6;
}
li:hover{
    border-bottom: 4px solid white;
}
</style>
