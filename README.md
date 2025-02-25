<!DOCTYPE html>
<html lang="en" data-bs-theme="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Android Reverse Engineering Resources | Tools & Guides</title>
    <meta name="description" content="Comprehensive collection of Android reverse engineering tools, emulators, tutorials, and community resources">
    <meta name="theme-color" content="#1a1a1a">

    <!-- Open Graph / Twitter -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://saksham.thedev.id/Reverse-Engineering/">
    <meta property="og:title" content="Android Reverse Engineering Resources | Tools & Guides">
    <meta property="og:description" content="Comprehensive collection of Android reverse engineering tools, emulators, tutorials, and community resources">
    <meta property="og:image" content="https://example.com/og-image.jpg">

    <!-- Bootstrap 5.3 -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css" rel="stylesheet">

    <style>
        :root {
            --gradient-start: #4f46e5;
            --gradient-end: #9333ea;
        }

        .category-card {
            background: linear-gradient(145deg, #1e1e1e, #2d2d2d);
            border-radius: 12px;
            transition: transform 0.2s ease;
        }

        .category-card:hover {
            transform: translateY(-5px);
        }

        .tool-link {
            color: #e0e0e0;
            text-decoration: none;
            padding: 0.75rem 1rem;
            border-radius: 8px;
            transition: all 0.2s ease;
        }

        .tool-link:hover {
            background: rgba(255, 255, 255, 0.05);
            color: #fff;
        }

        .section-header {
            background: linear-gradient(45deg, var(--gradient-start), var(--gradient-end));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
    </style>
</head>
<body class="bg-dark text-light">
    <header class="py-4 border-bottom border-secondary">
        <div class="container">
            <div class="d-flex flex-column flex-md-row justify-content-between align-items-center">
                <div class="text-center text-md-start mb-3 mb-md-0">
                    <h1 class="h2 fw-bold mb-2">Android Reverse Engineering</h1>
                    <p class="text-muted mb-0">Comprehensive resource collection for modding and analysis</p>
                </div>
                <a href="https://github.com/OshekharO/Reverse-Engineering"
                   class="btn btn-outline-light d-inline-flex align-items-center">
                    <i class="bi bi-github me-2"></i>
                    View on GitHub
                </a>
            </div>
        </div>
    </header>

    <main class="container py-5">
        <div class="text-center mb-5">
            <h1 class="h2 fw-bold mb-2">Reverse-Engineering</h1>
            <p class="text-muted mb-0">A collection of awesome Android app reverse engineering resources. Your contributions and suggestions are heartily welcome. (✿◕‿◕).</p>
        </div>

        <!-- Android Emulators -->
        <section class="mb-5">
            <h2 class="section-header h3 fw-bold mb-4"><i class="bi bi-phone me-2"></i>Android Emulators</h2>
            <div class="row g-4">
                <div class="col-md-6 col-lg-4">
                    <div class="category-card p-4 h-100">
                        <h3 class="h5 mb-3">Virtualization Tools</h3>
                        <div class="d-flex flex-column gap-2">
                            <a href="https://play.google.com/store/apps/details?id=com.pspace.vandroid"
                               class="tool-link" target="_blank">Virtual Android</a>
                            <a href="https://drive.google.com/uc?id=18uy6qDK7kJKPbTgsguOpBMm9Q2HnDn4B&export=download"
                               class="tool-link" target="_blank">VPhoneGaGa</a>
                            <a href="https://play.google.com/store/apps/details?id=com.redfinger.global"
                               class="tool-link" target="_blank">RedFinger</a>
                            <a href="https://github.com/FSpaceCore/SpaceCore/releases"
                               class="tool-link" target="_blank">DualMeta</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=1041895"
                               class="tool-link" target="_blank">Twoyi (Dead)</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=961828"
                               class="tool-link" target="_blank">Vmos Pro</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=1004655"
                               class="tool-link" target="_blank">X8 Sandbox</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=1004655"
                               class="tool-link" target="_blank">F1 VM</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Mobile Tools -->
        <section class="mb-5">
            <h2 class="section-header h3 fw-bold mb-4"><i class="bi bi-tools me-2"></i>Mobile Tools</h2>
            <div class="row g-4">
                <div class="col-md-6 col-lg-4">
                    <div class="category-card p-4 h-100">
                        <h3 class="h5 mb-3">APK Modification</h3>
                        <div class="d-flex flex-column gap-2">
                            <a href="https://github.com/timscriptov/ApkEditor"
                               class="tool-link" target="_blank">ApkEditor Pro</a>
                            <a href="https://github.com/AbdurazaaqMohammed/AXML-Editor"
                               class="tool-link" target="_blank">AXML Editor</a>
                            <a href="https://gofile.io/d/YLU7pP"
                               class="tool-link" target="_blank">XML Editor</a>
                            <a href="https://jasi2169.com/jasi-patcher/"
                               class="tool-link" target="_blank">Jasi Patcher</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=1037391"
                               class="tool-link" target="_blank">Apkanalyzer</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=548542"
                               class="tool-link" target="_blank">MT Manager</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=966965"
                               class="tool-link" target="_blank">NP Manager</a>
                            <a href="https://maximoff.su/apktool/?lang=en"
                               class="tool-link" target="_blank">APKTOOL M</a>
                            <a href="https://smalihelper.blogspot.com/"
                               class="tool-link" target="_blank">Smali Helper</a>
                            <a href="https://maximoff.su/mpatcher/"
                               class="tool-link" target="_blank">M-Patcher</a>
                            <a href="https://github.com/Maximoff/AEPatcher"
                               class="tool-link" target="_blank">AEPatcher</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=897774"
                               class="tool-link" target="_blank">Developer Assistant</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=958291"
                               class="tool-link" target="_blank">Dev Tools Pro</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=575450&view=findpost&p=62744086"
                               class="tool-link" target="_blank">Patches</a>
                            <a href="http://androidide.com"
                               class="tool-link" target="_blank">Android IDE</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=882654"
                               class="tool-link" target="_blank">ApkToolPatcher</a>
                            <a href="https://gofile.io/d/HDln2J"
                               class="tool-link" target="_blank">Java2Smali</a>
                            <a href="https://github.com/CodingGay/BlackDex"
                               class="tool-link" target="_blank">BlackDex</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=957572&st=60#entry92625117"
                               class="tool-link" target="_blank">Http Canary</a>
                            <a href="https://play.google.com/store/apps/details?id=com.reqable.android"
                               class="tool-link" target="_blank">Reqable</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=298302"
                               class="tool-link" target="_blank">Lucky Patcher</a>
                            <a href="https://4pda.to/forum/index.php?showtopic=780420"
                               class="tool-link" target="_blank">Jasi Patcher</a>
                            <a href="https://www.pling.com/p/2175692"
                               class="tool-link" target="_blank">Ads Regex</a>
                            <a href="https://github.com/AbdurazaaqMohammed/AntiSplit-M"
                               class="tool-link" target="_blank">Anti-Split</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- PC Tools -->
        <section class="mb-5">
            <h2 class="section-header h3 fw-bold mb-4"><i class="bi bi-pc me-2"></i>Desktop Tools</h2>
            <div class="row g-4">
                <div class="col-md-6 col-lg-4">
                    <div class="category-card p-4 h-100">
                        <h3 class="h5 mb-3">Analysis Suite</h3>
                        <div class="d-flex flex-column gap-2">
                            <a href="https://github.com/REAndroid/APKEditor"
                               class="tool-link" target="_blank">APKEditor</a>
                            <a href="https://github.com/Gameye98/DTL-X"
                               class="tool-link" target="_blank">DTL-X</a>
                            <a href="https://github.com/MrIkso/ApkRepacker"
                               class="tool-link" target="_blank">ApkRepacker</a>
                            <a href="https://github.com/MrIkso/ArscEditor"
                               class="tool-link" target="_blank">ArscEditor</a>
                            <a href="https://github.com/rizinorg/cutter"
                               class="tool-link" target="_blank">cutter</a>
                            <a href="https://ibotpeaches.github.io/Apktool/"
                               class="tool-link" target="_blank">Apktool</a>
                            <a href="https://github.com/pxb1988/dex2jar"
                               class="tool-link" target="_blank">DEX2JAR</a>
                            <a href="https://github.com/vaibhavpandeyvpz/apkstudio"
                               class="tool-link" target="_blank">Apk Studio</a>
                            <a href="https://forum.xda-developers.com/t/tool-windows-apk-easy-tool-v1-59-2-2021-04-03.3333960/"
                               class="tool-link" target="_blank">APK Easy Tool</a>
                            <a href="https://github.com/Konloch/bytecode-viewer"
                               class="tool-link" target="_blank">Bytecode Viewer</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Learning Resources -->
        <section class="mb-5">
            <h2 class="section-header h3 fw-bold mb-4"><i class="bi bi-journal-bookmark me-2"></i>Learning Resources</h2>
            <div class="row g-4">
                <div class="col-md-6">
                    <div class="category-card p-4 h-100">
                        <div class="d-flex flex-column gap-3">
                            <a href="https://github.com/OshekharO/Reverse-Engineering/wiki"
                               class="tool-link" target="_blank">
                                <i class="bi bi-file-text me-2"></i>
                                Smali Basics Guide
                            </a>
                            <a href="http://www.wiley.com/WileyCDA/WileyTitle/productCd-1118787315.html"
                               class="tool-link" target="_blank">
                                <i class="bi bi-book me-2"></i>
                                Practical Reverse Engineering
                            </a>
                            <a href="http://beginners.re/"
                               class="tool-link" target="_blank">
                                <i class="bi bi-book me-2"></i>
                                Reverse Engineering for Beginners
                            </a>
                            <a href="https://nostarch.com/idapro2.htm"
                               class="tool-link" target="_blank">
                                <i class="bi bi-book me-2"></i>
                                Reverse Engineering for Beginners
                            </a>
                            <a href="https://github.com/0x4143/malware-gems"
                               class="tool-link" target="_blank">
                                <i class="bi bi-book me-2"></i>
                                Reverse Engineering for Beginners
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-black py-4 mt-5">
        <div class="container text-center text-muted">
            <p class="mb-2">Maintained with <i class="bi bi-heart-fill text-danger"></i> by OshekharO</p>
            <p class="mb-0 small">&copy; 2024 Saksham Shekher. Educational use only.</p>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
