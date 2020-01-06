<template>
    <div class="fenlei">
        <header>
            <span>《</span>
            <span class="a1">分类</span>
            <span>首页</span>
        </header>
        <main>
            <div class='ipt'>
                <input type="text" placeholder="搜索品牌或商品">
            </div>
            
            <div class="box">
                <div class="left">
                    <li>男装女装</li>
                    <li>男装女装</li>
                    <li>男装女装</li>
                    <li>男装女装</li>
                    <li>男装女装</li>
                    <li>男装女装</li>
                </div>
                <div class="right">
                    <ul>
                        <li><img src="http://dummyimage.com/60x60" alt=""></li>
                        <li>京东</li>
                    </ul>
                    <ul>
                        <li><img src="http://dummyimage.com/60x60" alt=""></li>
                        <li>京东</li>
                    </ul>
                    <ul>
                        <li><img src="http://dummyimage.com/60x60" alt=""></li>
                        <li>京东</li>
                    </ul>
                    <ul>
                        <li><img src="http://dummyimage.com/60x60" alt=""></li>
                        <li>京东</li>
                    </ul>
                    <ul>
                        <li><img src="http://dummyimage.com/60x60" alt=""></li>
                        <li>京东</li>
                    </ul>
                    <ul>
                        <li><img src="http://dummyimage.com/60x60" alt=""></li>
                        <li>京东</li>
                    </ul>
                    <ul>
                        <li><img src="http://dummyimage.com/60x60" alt=""></li>
                        <li>京东</li>
                    </ul>
                    <ul>
                        <li><img src="http://dummyimage.com/60x60" alt=""></li>
                        <li>京东</li>
                    </ul>
                </div>
                </div> 
        </main>
        
    </div>
</template>

<script>
export default {

}
</script>

<style>
.fenlei{
    width: 100%;
    height: 100%;
    display: flex;
    flex-direction: column;
}
header{
    width: 100%;
    height: 50px;
    display: flex;
    justify-content: space-around;
    line-height:50px;
    background:#ccc;
}
.a1{
    display: block;
    width: 40%;
    height: 80%;
    background: #EEE;
    line-height: 40px;
    text-align: center;
}
main{
    width: 100%;
    flex: 1;
}
.box{
    width: 100%;
    height: 100%;
    display: flex;
}
.ipt{
    margin: 5px 0;
    width:100%;
    height:50px;
    display:flex;
    justify-content: center;
}
.ipt input{
    height: 50%;
    border: 1px solid #ccc;
    border-radius: 5px;
    padding-left: 10px;
}
.left{
    width: 30%;
    height: 100%;
    border-right: 1px solid #ccc;

}
.left li{
    margin: 5px 0;
    width: 100%;
    height: 40px;
    line-height: 40px;
    text-align: center;
}
.right{
    width: 69%;
    height: 100%;
    display: flex;
    flex-wrap: wrap;
}
.right ul{
    width: 23%;
    margin-left: 2px;
    display: flex;
    height: 100px;
    flex-direction: column;
    justify-content: center;
}
.right ul li{
    display: flex;
    justify-content: center;
}
</style>
