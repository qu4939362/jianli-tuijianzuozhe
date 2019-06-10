<template>
    <div id="app">
        <div class="content">
            <img class="recommend-banner" src="https://i.loli.net/2019/06/06/5cf8692246c4b40986.png" alt="">
            <a class="help" href="#"><i class="iconfont icon-wenhao"></i>如何成为签约作者</a>
            <div class="tuijian1">
                <div class="wrap">
                    <img src="https://i.loli.net/2019/06/03/5cf4d4d2a82e461470.jpg" alt="">
                    <div class="name"><h4><a href="#">穿着prada挤地铁</a></h4><i class="iconfont icon-woman"></i></div>
                    <p class="description"><a href="#">只写好玩的都市生活。
                        版权合作事宜请联系简...</a></p>
                    <div class="btn">
                        <span><a href="#">+关注</a></span>
                    </div>
                    <hr>
                    <div class="meta">最近更新</div>
                    <div class="recent-update">
                        <a href="#">好好利用邮件的自动回复automatic reply功能！</a>
                        <a href="#">病假、事假、年假...你会用英文和老板请假吗？</a>
                        <a href="#">20个你必须要知道的财务英语词汇</a>
                    </div>
                </div>
            </div>
            <div class="tuijian1">
                <div class="wrap">
                    <img src="https://i.loli.net/2019/06/04/5cf5d6d56ea2012656.jpg" alt="">
                    <div class="name"><h4><a href="#">吴晓布</a></h4></div>
                    <p class="description"><a href="#">简书签约作者，商业管理优秀作者，视觉优秀作者...</a></p>
                    <div class="btn">
                        <span><a href="#">+关注</a></span>
                    </div>
                    <hr>
                    <div class="meta">最近更新</div>
                    <div class="recent-update">
                        <a href="#">《认知:所谓成长就是认知升级》签名版赠书活动</a>
                        <a href="#">关于读书日</a>
                        <a href="#">书出版了，我想和你们聊聊这些</a>
                    </div>
                </div>
            </div>
            <div class="tuijian1">
                <div class="wrap">
                    <img src="https://i.loli.net/2019/06/04/5cf5d7fa8451472983.jpeg" alt="">
                    <div class="name"><h4><a href="#">茶点故事</a></h4></div>
                    <p class="description"><a href="#">简书上的好故事，我！承！包！了！
                        本账...</a></p>
                    <div class="btn">
                        <span><a href="#">+关注</a></span>
                    </div>
                    <hr>
                    <div class="meta">最近更新</div>
                    <div class="recent-update">
                        <a href="#">茶点有毒：不用在意别人怎么看你</a>
                        <a href="#">送外卖，让我见识了世间百态</a>
                        <a href="#">简圈冷笑话：不要把鸡蛋放在同一个篮子里</a>
                    </div>
                </div>
            </div>
            <div class="tuijian1">
                <div class="wrap">
                    <img src="https://i.loli.net/2019/06/04/5cf5e308adad924123.png" alt="">
                    <div class="name"><h4><a href="#">简书大学堂</a></h4></div>
                    <p class="description"><a href="#">全网最具艺术感的手绘课：
                        https://...</a></p>
                    <div class="btn">
                        <span><a href="#">+关注</a></span>
                    </div>
                    <hr>
                    <div class="meta">最近更新</div>
                    <div class="recent-update">
                        <a href="#">写作，是普通人加速蜕变的必备技能</a>
                        <a href="#">一次大胆的尝试，让你我与大师相遇</a>
                        <a href="#">「春日活动」获奖名单公布</a>
                    </div>
                </div>
            </div>
            <div class="tuijian1">
                <div class="wrap">
                    <img src="https://i.loli.net/2019/06/04/5cf6083b1219597761.png" alt="">
                    <div class="name"><h4><a href="#">北美之北</a></h4><i class="iconfont icon-woman(2)"></i></div>
                    <p class="description"><a href="#">是：老司机/奶爸/吃货
                        写：职场的坑/父女...</a></p>
                    <div class="btn">
                        <span><a href="#">+关注</a></span>
                    </div>
                    <hr>
                    <div class="meta">最近更新</div>
                    <div class="recent-update">
                        <a href="#">自带音效的烟花</a>
                        <a href="#">路过一家医院</a>
                        <a href="#">加拿大幼儿园的作业：美食排行榜</a>
                    </div>
                </div>
            </div>
            <div class="tuijian1">
                <div class="wrap">
                    <img src="https://i.loli.net/2019/06/04/5cf60aa3f35c860956.png" alt="">
                    <div class="name"><h4><a href="#">冰千里</a></h4><i class="iconfont icon-woman"></i></div>
                    <p class="description"><a href="#">私人执业心理咨询师
                        主攻亲密关系
                        筹...</a></p>
                    <div class="btn">
                        <span><a href="#">+关注</a></span>
                    </div>
                    <hr>
                    <div class="meta">最近更新</div>
                    <div class="recent-update">
                        <a href="#">“别难过了，一切都会好起来的”， “滚！”。</a>
                        <a href="#">多数痛苦，来自家庭角色的错位</a>
                        <a href="#">痛苦两个极端：“核心价值被摧毁”与“核心痛点被暴露”</a>
                    </div>
                </div>
            </div>
        </div>
        <a class="btn btn-danger" href="#">加载更多</a>
    </div>
</template>

<script>
    import "normalize.css"

    export default {
        name: "tuijian"
    }
</script>

<style scoped>
    * {
        margin: 0px;
        padding: 0px;
    }

    #app {
        width: 100%;
        height: 100%;
        display: flex;
        align-items: center;
        flex-direction: column;
    }

    .content {
        width: 70%;
        text-align: center;
        display: flex;
        flex-wrap: wrap;
    }
    .help {
        position: absolute;
        right: 247px;
        top: 44px;
        text-decoration: none;
        color: #ffffff;
    }
    .recommend-banner {
        width: 100%;
        height: 16%;
        background-color: hsla(0, 0%, 71%, .2);
        border-radius: 6px;
    }

    img {
        vertical-align: middle;
    }

    .tuijian1 {
        width: 30%;
        padding: 0 15px;
    }

    .wrap {
        width: 100%;
        height: 320px;
        /*padding: 0 20px;*/
        margin-top: 80px;
        background-color: #e6e6e6;
        /*display: flex;*/
        /*justify-content: center;*/
        /*flex-direction: row;*/
        border-radius: 10px;
        background-color: hsla(0, 0%, 71%, .1);
    }

    .wrap img {
        border-radius: 40px;
        width: 80px;
        height: 80px;
        margin: -40px 0 10px;
        display: inline-block;
        border: 1px solid #ddd;
        background-color: #fff;
    }

    .name h4 {
        display: inline-block;
        font-size: 21px;
        font-weight: 700;
        text-overflow: ellipsis;
        white-space: nowrap;
    }

    .name h4 a {
        color: #333333;
        text-decoration: none;
    }

    .icon-woman {
        color: #ea6f5a;
        width: 21px;
        height: 22px;
    }

    .description {
        width: 55%;
        height: 50px;
        min-height: 50px;
        font-size: 13px;
        line-height: 25px;
        margin-left: 22%;
        margin-top: 15px;
    }

    .description a {
        color: #333333;
        text-decoration: none;
    }

    .btn {
        border-radius: 40px;
        color: #fff;
        background-color: #42c02e;
        width: 100px;
        padding: 8px 0;
        margin-left: 35%;
        line-height: normal;
        margin-top: 10px;
    }

    .btn span a {
        text-decoration: none;
        color: white;
    }

    hr {
        margin-top: 20px;
        margin-bottom: 20px;
        border-top: 1px solid;
        border-color: #eaeaea;
        margin-left: 17%;
        width: 73%;
    }

    .meta {
        float: left;
        margin-top: -29px;
        padding-right: 10px;
        font-size: 12px;
        color: #969696;
        width: 48px;
        margin-left: 9%;
    }

    .recent-update a {
        color: #333;
        font-size: 13px;
        line-height: 25px;
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
        display: block;
        text-decoration: none;
    }

    .recent-update :hover {
        text-decoration: underline;
    }

    .btn-danger {
        display: flex;
        justify-content: center;
        justify-items: center;
        width: 27.2%;
        padding: 10px 0;
        margin: 40px 0;
        font-size: 15px;
        border-radius: 20px;
        background-color: #a5a5a5;
        border: none;
        text-decoration: none;
    }

</style>