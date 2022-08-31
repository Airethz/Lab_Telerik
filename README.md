# Lab_Telerik


<ol>
    <li>
        下載官網提供的<a href="https://www.telerik.com/try/ui-for-blazor?_ga=2.211848980.1429587012.1661839889-225411112.1656902543#login">Telerik NuGet Feed</a>(需登入Telerik)
    </li>
    <li>
        安裝執行檔
    </li>
    <li>
        選擇安裝產品(依個人需求)
        <div>
            <img src="https://github.com/Airethz/Lab_Telerik/blob/main/src/Lab_Telerik/wwwroot/Image/1.png" height="500" />
        </div>
    </li>
    <li>
        點擊「Next」
    </li>
    <li>
        在「options」頁面勾選「Set up Telerik NuGet package source」
        <div>
            <img src="https://github.com/Airethz/Lab_Telerik/blob/main/src/Lab_Telerik/wwwroot/Image/2.png" height="500" />
        </div>
    </li>
    <li>
        點擊「Install」進行安裝
    </li>
    <li>
        在專案的Nuget新增「專案來源」並選擇(使用時登入畫面，輸入Telerik帳密)
        <ul>
            <li>
                來源：https://nuget.telerik.com/v3/index.json
                <div>
                    <img src="https://github.com/Airethz/Lab_Telerik/blob/main/src/Lab_Telerik/wwwroot/Image/3.png" height="300" />
                </div>
            </li>
        </ul>
    </li>
    <li>
        安裝「套件：Telerik.UI.for.Blazor.Trial」
    </li>
    <li>
        _Host.cshtml加入以下css及javascript：
        <ul>
            <li>
                &lt;link rel="stylesheet" href="_content/Telerik.UI.for.Blazor.Trial/css/kendo-theme-default/all.css" /&gt;
            </li>
            <li>
                &lt;script src="_content/Telerik.UI.for.Blazor.Trial/js/telerik-blazor.js" defer&gt;&lt;/script&gt;
            </li>
        </ul>
    </li>
    <li>
        Startup.cs的ConfigureServices加入：
        <ul>
            <li>
                services.AddTelerikBlazor();
            </li>
        </ul>
    </li>
    <li>
        MainLayout.razor的Body做調整(TelerikRootComponent)：
        <ul>
            <li>
                <a href="https://docs.telerik.com/blazor-ui/getting-started/what-you-need#project-configuration">官方文件</a>
                <div>
                    <img src="https://github.com/Airethz/Lab_Telerik/blob/main/src/Lab_Telerik/wwwroot/Image/4.png" height="300" />
                </div>
            </li>
        </ul>
    </li>
</ol>
