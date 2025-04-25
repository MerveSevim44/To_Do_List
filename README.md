<h1 data-start="98" data-end="120" class="">ToDo List Projesi 📋</h1>
<p data-start="122" data-end="345" class=""><strong data-start="122" data-end="143">ToDo List Projesi</strong>, basit bir görev yönetimi uygulamasıdır. Kullanıcılar, günlük işlerini takip etmek için bu uygulamayı kullanabilirler. 
  Bu proje, <strong data-start="273" data-end="314">WPF (Windows Presentation Foundation)</strong> kullanılarak geliştirilmiştir.</p>
  <h2 data-start="347" data-end="366" class="">Teknolojiler 🛠️</h2>
  <ul data-start="367" data-end="471">
<li data-start="367" data-end="393" class="" style="">
<p data-start="369" data-end="393" class=""><strong data-start="369" data-end="389">Programlama Dili</strong>: C#</p>
</li>
<li data-start="394" data-end="433" class="" style="">
<p data-start="396" data-end="433" class=""><strong data-start="396" data-end="417">Çerçeve/Framework</strong>: .NET 9.0 (WPF)</p>
</li>
<li data-start="434" data-end="471" class="" style="">
<p data-start="436" data-end="471" class=""><strong data-start="436" data-end="454">UI Teknolojisi</strong>: XAML (WPF için)</p>
</li>
</ul>
<h2 data-start="473" data-end="491" class="">Proje Yapısı 📂</h2>
<pre class="overflow-visible!" data-start="493" data-end="1323"><div class="contain-inline-size rounded-md border-[0.5px] border-token-border-medium relative bg-token-sidebar-surface-primary"><div class="flex items-center text-token-text-secondary px-4 py-2 text-xs font-sans justify-between h-9 bg-token-sidebar-surface-primary dark:bg-token-main-surface-secondary select-none rounded-t-[5px]">pgsql</div><div class="sticky top-9"><div class="absolute end-0 bottom-0 flex h-9 items-center pe-2"><div class="bg-token-sidebar-surface-primary text-token-text-secondary dark:bg-token-main-surface-secondary flex items-center rounded-sm px-2 font-sans text-xs"><span class="" data-state="closed"><button class="flex gap-1 items-center select-none px-4 py-1" aria-label="Kopyala"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-xs"><path fill-rule="evenodd" clip-rule="evenodd" d="M7 5C7 3.34315 8.34315 2 10 2H19C20.6569 2 22 3.34315 22 5V14C22 15.6569 20.6569 17 19 17H17V19C17 20.6569 15.6569 22 14 22H5C3.34315 22 2 20.6569 2 19V10C2 8.34315 3.34315 7 5 7H7V5ZM9 7H14C15.6569 7 17 8.34315 17 10V15H19C19.5523 15 20 14.5523 20 14V5C20 4.44772 19.5523 4 19 4H10C9.44772 4 9 4.44772 9 5V7ZM5 9C4.44772 9 4 9.44772 4 10V19C4 19.5523 4.44772 20 5 20H14C14.5523 20 15 19.5523 15 19V10C15 9.44772 14.5523 9 14 9H5Z" fill="currentColor"></path></svg>Kopyala</button></span><span class="" data-state="closed"><button class="flex items-center gap-1 px-4 py-1 select-none"><svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="icon-xs"><path d="M2.5 5.5C4.3 5.2 5.2 4 5.5 2.5C5.8 4 6.7 5.2 8.5 5.5C6.7 5.8 5.8 7 5.5 8.5C5.2 7 4.3 5.8 2.5 5.5Z" fill="currentColor" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"></path><path d="M5.66282 16.5231L5.18413 19.3952C5.12203 19.7678 5.09098 19.9541 5.14876 20.0888C5.19933 20.2067 5.29328 20.3007 5.41118 20.3512C5.54589 20.409 5.73218 20.378 6.10476 20.3159L8.97693 19.8372C9.72813 19.712 10.1037 19.6494 10.4542 19.521C10.7652 19.407 11.0608 19.2549 11.3343 19.068C11.6425 18.8575 11.9118 18.5882 12.4503 18.0497L20 10.5C21.3807 9.11929 21.3807 6.88071 20 5.5C18.6193 4.11929 16.3807 4.11929 15 5.5L7.45026 13.0497C6.91175 13.5882 6.6425 13.8575 6.43197 14.1657C6.24513 14.4392 6.09299 14.7348 5.97903 15.0458C5.85062 15.3963 5.78802 15.7719 5.66282 16.5231Z" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path><path d="M14.5 7L18.5 11" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg>Düzenle</button></span></div></div></div><div class="overflow-y-auto p-4" dir="ltr"><code class="whitespace-pre!"><span><span>ToDoList/
├── ToDoList.sln
└── ToDoList/
    ├── App.xaml
    ├── App.xaml.cs
    ├── AssemblyInfo.cs
    ├── MainWindow.xaml
    ├── MainWindow.xaml.cs
    ├── ToDoList.csproj
    ├── bin/
    │   └── </span><span><span class="hljs-keyword">Debug</span></span><span>/
    │       └── net9</span><span><span class="hljs-number">.0</span></span><span>-windows/
    │           ├── ToDoList.deps.json
    │           └── ToDoList.runtimeconfig.json
    └── obj/
        ├── project.assets.json
        ├── project.nuget.cache
        ├── ToDoList.csproj.nuget.dgspec.json
        ├── ToDoList.csproj.nuget.g.props
        ├── ToDoList.csproj.nuget.g.targets
        └── </span><span><span class="hljs-keyword">Debug</span></span><span>/
            └── net9</span><span><span class="hljs-number">.0</span></span><span>-windows/
                ├── App.g.cs
                ├── MainWindow.baml
                ├── MainWindow.g.cs
                ├── ToDoList.AssemblyInfo.cs
                ├── ToDoList.assets.cache
                └── ToDoList.GlobalUsings.g.cs
</span></span></code></div></div></pre>
<h3 data-start="1325" data-end="1342" class="">Ana Dosyalar:</h3>
<ul data-start="1343" data-end="1688">
<li data-start="1343" data-end="1419" class="" style="">
<p data-start="1345" data-end="1419" class=""><strong data-start="1345" data-end="1357">App.xaml</strong>: Uygulamanın başlatılmasını ve temel yapılandırmasını içerir.</p>
</li>
<li data-start="1420" data-end="1495" class="" style="">
<p data-start="1422" data-end="1495" class=""><strong data-start="1422" data-end="1437">App.xaml.cs</strong>: <code data-start="1439" data-end="1449">App.xaml</code> dosyasına karşılık gelen C# kodlarını içerir.</p>
</li>
<li data-start="1496" data-end="1567" class="" style="">
<p data-start="1498" data-end="1567" class=""><strong data-start="1498" data-end="1517">MainWindow.xaml</strong>: Uygulamanın ana penceresinin tasarım dosyasıdır.</p>
</li>
<li data-start="1568" data-end="1631" class="" style="">
<p data-start="1570" data-end="1631" class=""><strong data-start="1570" data-end="1592">MainWindow.xaml.cs</strong>: Ana pencere için işlevsel C# kodları.</p>
</li>
<li data-start="1632" data-end="1688" class="" style="">
<p data-start="1634" data-end="1688" class=""><strong data-start="1634" data-end="1653">ToDoList.csproj</strong>: Projenin yapılandırma dosyasıdır.</p>
</li>
</ul>

<h3 data-start="1690" data-end="1716" class="">Bin ve Obj Klasörleri:</h3>
<ul data-start="1717" data-end="1851">
<li data-start="1717" data-end="1791" class="" style="">
<p data-start="1719" data-end="1791" class=""><strong data-start="1719" data-end="1727">bin/</strong>: Derleme sonrası çıkan derlenmiş dosyalar bu klasörde yer alır.</p>
</li>
<li data-start="1792" data-end="1851" class="" style="">
<p data-start="1794" data-end="1851" class=""><strong data-start="1794" data-end="1802">obj/</strong>: Projeyle ilgili geçici dosyalar burada bulunur.</p>
</li>
</ul>

<h2 data-start="1853" data-end="1866" class="">Kurulum 🔧</h2>
<ol data-start="1868" data-end="1893">
<li data-start="1868" data-end="1893" class="" style="">
<p data-start="1871" data-end="1893" class=""><strong data-start="1871" data-end="1892">Repo'yu Klonlayın</strong>:</p>
</li>
</ol>




