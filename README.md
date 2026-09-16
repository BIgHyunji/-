# -
허현지를 소개하는 !!
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>허현지 공주 | AI 리터러시 지도사 & 전문 강사</title>
    <!-- Pretendard Font & FontAwesome Icon -->
    <link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.min.css" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-blue: #0A2540;
            --accent-gold: #D4AF37;
            --soft-bg: #F8FAFC;
            --card-bg: #FFFFFF;
            --text-main: #1E293B;
            --text-sub: #64748B;
            --shadow-3d: 0 20px 25px -5px rgba(10, 37, 64, 0.1), 0 8px 10px -6px rgba(10, 37, 64, 0.1);
            --border-radius: 16px;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: "Pretendard Variable", Pretendard, -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
            word-break: keep-all;
        }

        body {
            background-color: var(--soft-bg);
            color: var(--text-main);
            line-height: 1.6;
            scroll-behavior: smooth;
        }

        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, var(--primary-blue) 0%, #1E3A8A 100%);
            color: #FFFFFF;
            padding: 100px 0 80px;
            text-align: center;
            position: relative;
            box-shadow: var(--shadow-3d);
        }

        .hero-badge {
            display: inline-block;
            background: rgba(212, 175, 55, 0.2);
            color: var(--accent-gold);
            border: 1px solid var(--accent-gold);
            padding: 6px 16px;
            border-radius: 30px;
            font-size: 0.9rem;
            font-weight: 600;
            margin-bottom: 20px;
        }

        .hero h1 {
            font-size: 2.8rem;
            font-weight: 800;
            margin-bottom: 16px;
            letter-spacing: -0.5px;
        }

        .hero p {
            font-size: 1.25rem;
            color: #E2E8F0;
            max-width: 700px;
            margin: 0 auto 30px;
            font-weight: 300;
        }

        .cta-btn {
            display: inline-block;
            background: var(--accent-gold);
            color: var(--primary-blue);
            font-weight: 700;
            padding: 16px 36px;
            border-radius: 50px;
            text-decoration: none;
            box-shadow: 0 10px 20px rgba(212, 175, 55, 0.3);
            transition: all 0.3s ease;
        }

        .cta-btn:hover {
            transform: translateY(-3px) scale(1.02);
            box-shadow: 0 15px 25px rgba(212, 175, 55, 0.4);
        }

        /* Section Global */
        section {
            padding: 80px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 50px;
        }

        .section-title h2 {
            font-size: 2rem;
            color: var(--primary-blue);
            font-weight: 700;
            margin-bottom: 10px;
        }

        .section-title p {
            color: var(--text-sub);
            font-size: 1.05rem;
        }

        /* Grid Layouts & 3D Cards */
        .grid-3 {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
        }

        .grid-4 {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
            gap: 20px;
        }

        .card-3d {
            background: var(--card-bg);
            border-radius: var(--border-radius);
            padding: 32px 24px;
            box-shadow: var(--shadow-3d);
            border: 1px solid rgba(226, 232, 240, 0.8);
            transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
            position: relative;
            top: 0;
        }

        .card-3d:hover {
            top: -8px;
            box-shadow: 0 25px 30px -10px rgba(10, 37, 64, 0.15);
            border-color: var(--accent-gold);
        }

        .card-icon {
            width: 50px;
            height: 50px;
            background: rgba(10, 37, 64, 0.05);
            color: var(--primary-blue);
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            margin-bottom: 20px;
        }

        .card-3d h3 {
            font-size: 1.25rem;
            margin-bottom: 12px;
            color: var(--primary-blue);
        }

        .card-3d p {
            color: var(--text-sub);
            font-size: 0.95rem;
            line-height: 1.6;
        }

        /* About & Identity Highlight */
        .identity-box {
            background: #FFFFFF;
            border-radius: var(--border-radius);
            padding: 40px;
            box-shadow: var(--shadow-3d);
            border-left: 6px solid var(--accent-gold);
            margin-bottom: 40px;
        }

        /* Check List */
        .checklist {
            list-style: none;
        }

        .checklist li {
            position: relative;
            padding-left: 30px;
            margin-bottom: 15px;
            font-size: 1.05rem;
            color: var(--text-main);
        }

        .checklist li::before {
            content: "✓";
            position: absolute;
            left: 0;
            top: 0;
            color: var(--accent-gold);
            font-weight: 900;
            font-size: 1.2rem;
        }

        /* Footer */
        footer {
            background: var(--primary-blue);
            color: #94A3B8;
            padding: 40px 0;
            text-align: center;
            font-size: 0.9rem;
        }

        /* Top Button */
        #topBtn {
            position: fixed;
            bottom: 30px;
            right: 30px;
            width: 55px;
            height: 55px;
            background: var(--accent-gold);
            color: var(--primary-blue);
            border: none;
            border-radius: 50%;
            cursor: pointer;
            font-weight: bold;
            font-size: 0.85rem;
            box-shadow: 0 10px 20px rgba(0,0,0,0.2);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s ease;
            z-index: 1000;
        }

        #topBtn i {
            font-size: 1rem;
            margin-bottom: 2px;
        }

        #topBtn.show {
            opacity: 1;
            visibility: visible;
        }

        #topBtn:hover {
            background: #FFFFFF;
            transform: translateY(-50px) scale(1.1);
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero h1 { font-size: 2rem; }
            .hero p { font-size: 1rem; }
            section { padding: 50px 0; }
            .identity-box { padding: 25px; }
            #topBtn { bottom: 20px; right: 20px; width: 48px; height: 48px; font-size: 0.75rem; }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <header class="hero">
        <div class="container">
            <span class="hero-badge">AI Literacy & Public Sector Expert</span>
            <h1>미래를 인지하고 시대를 이끄는<br>AI 리터러시 전문 가이드, 허현지</h1>
            <p>공공기관의 신뢰감과 떡볶이처럼 매콤하고 강렬한 입담으로 청중을 매료시키는 차세대 전문 강사</p>
            <a href="#contact" class="cta-btn">강의 및 섭외 문의하기</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about">
        <div class="container">
            <div class="identity-box">
                <h3 style="font-size: 1.5rem; color: var(--primary-blue); margin-bottom: 15px;">"안성의 자랑, 낮에는 성실한 꿀벌 일개미 🐝"</h3>
                <p style="color: var(--text-sub); font-size: 1.05rem;">
                    국민건강보험공단에서 꿀(실적)을 모으듯 쌓아올린 실무 전문성과 체계적인 데이터 역량. 
                    퇴근 후엔 떡볶이 수혈과 반려견 '두콩이'의 힐링을 바탕으로 한 지치지 않는 에너지를 발산합니다. 
                    단순한 기술 전달을 넘어 청중의 눈을 번쩍 뜨이게 만들고 집중도를 300% 올려주는 명쾌한 AI 리터러시 강의를 제공합니다.
                </p>
            </div>
        </div>
    </section>

    <!-- Key Pillars Section -->
    <section style="background-color: #F1F5F9;">
        <div class="container">
            <div class="section-title">
                <h2>4 Core Pillars</h2>
                <p>허현지 강사를 완성하는 4가지 시그니처 역량</p>
            </div>
            <div class="grid-4">
                <div class="card-3d">
                    <div class="card-icon"><i class="fa-solid fa-bee"></i></div>
                    <h3>🐝 꿀벌 행세 (실무력)</h3>
                    <p>공공기관 현장에서 검증된 부지런함과 공감대 형성 능력. 조직의 맥락을 완벽히 이해하는 맞춤형 강좌 진행.</p>
                </div>
                <div class="card-3d">
                    <div class="card-icon"><i class="fa-solid fa-fire"></i></div>
                    <h3>🥘 떡볶이 (열정)</h3>
                    <p>혈관에 흐르는 매콤한 열정! 지루할 틈 없이 톡 쏘는 입담과 중독성 있는 몰입감 넘치는 강의 스타일.</p>
                </div>
                <div class="card-3d">
                    <div class="card-icon"><i class="fa-solid fa-eye"></i></div>
                    <h3>😍 눈정화 (집중도)</h3>
                    <p>잘생긴 남자를 볼 때처럼 청중의 눈을 번쩍 뜨이게 만드는 명료한 전달력과 시각적 몰입 기법 제시.</p>
                </div>
                <div class="card-3d">
                    <div class="card-icon"><i class="fa-solid fa-dog"></i></div>
                    <h3>🐶 두콩이 (멘탈케어)</h3>
                    <p>마스코트 두콩이급의 마성 매력! 청중의 스트레스를 날려버리는 유쾌하고 편안한 강의 환경 조성.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Services / Curriculum Section -->
    <section>
        <div class="container">
            <div class="section-title">
                <h2>AI 교육 프로그램</h2>
                <p>기업 및 공공기관 맞춤형 AI 리터러시 커리큘럼</p>
            </div>
            <div class="grid-3">
                <div class="card-3d">
                    <h3>공공기관 맞춤형 AI 활용법</h3>
                    <p>행정 효율 극대화 및 업무 자동화를 위한 프롬프트 엔지니어링 실무 교육.</p>
                </div>
                <div class="card-3d">
                    <h3>AI 리터러시 & 윤리 교육</h3>
                    <p>인공지능 시대를 살아가는 현대인을 위한 필수 비판적 사고 및 윤리 가이드라인 제공.</p>
                </div>
                <div class="card-3d">
                    <h3>생성형 AI 업무 적용 워크숍</h3>
                    <p>실제 업무 문서 작성 및 데이터 분석을 단시간에 해결하는 입문자 맞춤형 워크숍.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Client Checklist & FAQ Section -->
    <section style="background-color: #F1F5F9;">
        <div class="container">
            <div class="section-title">
                <h2>담당자 체크리스트 & FAQ</h2>
                <p>교육 관계자분들의 명쾌한 의사결정을 돕는 가이드</p>
            </div>
            <div class="grid-3">
                <div class="card-3d" style="grid-column: span 1;">
                    <h3 style="margin-bottom: 20px;">섭외 체크리스트</h3>
                    <ul class="checklist">
                        <li>강사의 확실한 전달력과 실무 전문성이 필요한가?</li>
                        <li>꿀벌처럼 부지런하고 유쾌한 강사를 찾는가?</li>
                        <li>오늘따라 떡볶이가 땡기는가?</li>
                    </ul>
                    <p style="margin-top: 15px; font-weight: 600; color: var(--primary-blue);">3개 모두 체크 시 섭외 확정 권장!</p>
                </div>
                <div class="card-3d" style="grid-column: span 2;">
                    <h3 style="margin-bottom: 20px;">자주 묻는 질문 (FAQ)</h3>
                    <div style="margin-bottom: 15px;">
                        <strong>Q. 안성 거주자이신데 전국 출강이 가능한가요?</strong>
                        <p>A. 꿀벌 날개를 달고 대한민국 어디든 신속하게 달려갑니다!</p>
                    </div>
                    <div>
                        <strong>Q. 공주님 컨셉이라 강의가 가벼우면 어쩌죠?</strong>
                        <p>A. 본업 모먼트에서는 누구보다 엄격하고 전문적인 AI 리터러시 지도사로서 완성도 높은 강의를 제공합니다.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer & Contact -->
    <footer id="contact">
        <div class="container">
            <h2 style="color: #FFFFFF; margin-bottom: 15px;">허현지 공주 x AI 리터러시 지도사</h2>
            <p style="margin-bottom: 20px;">강의 문의 및 섭외 요청은 언제든 환영합니다.</p>
            <p>© 2026 Hyeonji Huh. All Rights Reserved.</p>
        </div>
    </footer>

    <!-- Top Floating Button -->
    <button id="topBtn" onclick="scrollToTop()">
        <i class="fa-solid fa-chevron-up"></i>
        <span>맨위</span>
    </button>

    <script>
        // Top Button Visibility
        const topBtn = document.getElementById("topBtn");

        window.onscroll = function() {
            if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
                topBtn.classList.add("show");
            } else {
                topBtn.classList.remove("show");
            }
        };

        // Scroll to Top Function
        function scrollToTop() {
            window.scrollTo({
                top: 0,
                behavior: "smooth"
            });
        }
    </script>
</body>
</html>
