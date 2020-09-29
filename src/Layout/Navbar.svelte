<!-- Header Component -->
<script>



</script>

<div class="navbar-wrapper">
    <span>I'm the Navbar Component.</span>
    <!-- 圖片這裡試著做一個限時動態的功能 -->
    <!-- 我是一個對什麼都有感覺的人，樂於分享 -->
    <div class="selfie-photo"></div>
    <h2>豆腐</h2>
    <!-- 放喜歡的句子 -->
    <p>A creative, organized Front-End developer,highly interested in visual design and web development. Enjoy solving problems.</p>
    <p>工作經歷約 5 年，網頁設計經歷 3 年，目前正朝著前端工程師邁進。</p>
    <div class="social-links">
        <ul>
            <li>Github</li>
            <li>Medium</li>
            <li>CakeResume</li>
            <li>LinkedIn</li>
            <li>E-mail</li>
            <!-- 這裡可能要用 icon 或是圖片 -->
        </ul>
    </div>
    <div class="tags">
        <ul>
            <li>Frontend Engineer</li>
            <li>雙魚座</li>
            <li>網頁設計師</li>
            <li>愛麗 EXO-L</li>
            <li>熱愛閱讀</li>
            <li>運動</li>
            <li>拍立得</li>
            <li>即可拍</li>
            <li>Max media 麥瑟創意策略有限公司</li>
            <li>Ashlieworks 艾璽數位媒體有限公司</li>
            <li>Tripresso 玩咖旅行社</li>
        </ul>
    </div>
    <div class="links">
        <ul>
            <!-- 這個是討論個性，可以用視覺化工具 D3.js 處理 -->
            <li>基因組成</li>
            <li>感興趣的事</li>
            <li>目標</li>
            <li>技能樹</li>
            <li>經驗分享</li>
            <li>閱讀清單</li>
            <li>都是經歷</li>
            <!-- 這裡要拆成兩個分類，設計、前端 -->
            <li>相關作品</li>

            <!-- 技術/寫程式相關的事 -->
            <!-- Year Review 是一個主題，例如每天走幾步 -->
            <!-- 想把我的運動紀錄也放上來 -->
        </ul>
    </div>
</div>

<style>
    /* TODO - 研究如何引入 SASS */
    .navbar-wrapper{
        background: #000;
        color: azure;
    }
    .selfie-photo{
        width: 10em;
        height: 10em;
        border-radius: 100%;
        background-image: url('../../img/selfie_photo.jpg');
        background-size: cover;
        background-position: center;
        margin: 0 auto;
    }

    ul{
        display: flex;
        justify-content: center;
    }

    li{
        margin: .2rem;
    }

    .tags{
        margin: 0 auto;
        width: 100%;
    }

   

    .tags ul li{
        background: #fff;
        border-radius: 4px;
        color: #000;
        padding: .2rem .6rem;
    }

    .tags ul li:before{
        content: '#';
    }

    .links{
        margin: 0 auto;
        width: 100%;
    }

    .links li{
        font-size: 2rem;
    }
    
</style>

