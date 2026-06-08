<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>امتحان فسيولوجيا النبات - جامعة سوهاج | كلية العلوم</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            background: linear-gradient(135deg, #eef5f0, #d4e3da);
            font-family: 'Segoe UI', 'Tahoma', 'Arial', sans-serif;
            padding: 25px 20px;
            color: #1a3a2c;
        }
        .exam-container {
            max-width: 1200px;
            margin: 0 auto;
            background: #fffffffa;
            border-radius: 50px;
            box-shadow: 0 20px 35px rgba(0, 30, 0, 0.2);
            padding: 30px 35px 50px;
            border: 1px solid #c2e0d0;
        }
        /* header */
        .uni-header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 20px;
            margin-bottom: 25px;
            padding-bottom: 20px;
            border-bottom: 3px solid #2c7a5a;
        }
        .uni-title h2 {
            color: #155a3b;
            font-size: 1.6rem;
        }
        .uni-title p {
            font-size: 0.9rem;
            color: #2d6a4f;
        }
        .profile-area {
            display: flex;
            align-items: center;
            gap: 12px;
            background: #eef7f2;
            padding: 8px 18px;
            border-radius: 60px;
        }
        .profile-img {
            width: 65px;
            height: 65px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #2c7a5a;
            background: white;
        }
        .exam-meta {
            background: #e9f3ef;
            padding: 12px 20px;
            border-radius: 40px;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 15px;
            margin-bottom: 30px;
            font-weight: bold;
        }
        .section-title {
            font-size: 1.8rem;
            background: #cbe5db;
            display: inline-block;
            padding: 5px 28px;
            border-radius: 45px;
            margin: 25px 0 20px 0;
        }
        .question-card {
            background: white;
            border-radius: 28px;
            margin-bottom: 28px;
            padding: 18px 24px;
            box-shadow: 0 5px 12px rgba(0, 0, 0, 0.05);
            border-right: 6px solid #349b6e;
        }
        .q-title {
            display: flex;
            align-items: baseline;
            gap: 12px;
            flex-wrap: wrap;
            margin-bottom: 15px;
        }
        .q-num {
            background: #2a7a5c;
            color: white;
            border-radius: 35px;
            padding: 3px 16px;
            font-size: 0.85rem;
        }
        .q-text {
            font-weight: 700;
            font-size: 1.1rem;
        }
        .options {
            margin: 12px 0 15px 20px;
        }
        .option {
            margin: 8px 0;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        button.check-btn {
            background: #266b4e;
            border: none;
            color: white;
            padding: 6px 24px;
            border-radius: 40px;
            font-weight: bold;
            cursor: pointer;
            margin-top: 10px;
            transition: 0.2s;
        }
        button.check-btn:hover {
            background: #1b523d;
            transform: scale(0.97);
        }
        .feedback {
            margin-top: 12px;
            padding: 8px 18px;
            border-radius: 35px;
            font-weight: 500;
            display: inline-block;
        }
        .correct-feedback {
            background: #daf4e9;
            color: #0a4a2f;
            border-right: 4px solid #1f9e6e;
        }
        .wrong-feedback {
            background: #ffe2db;
            color: #b03318;
            border-right: 4px solid #e35f3e;
        }
        .essay-btn {
            background: #4f7a66;
            margin-left: 15px;
        }
        .model-answer {
            background: #f8faf7;
            padding: 12px 20px;
            border-radius: 20px;
            margin-top: 15px;
            border-right: 4px solid #2c7a5a;
            color: #1f4d3a;
        }
        hr {
            margin: 20px 0;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.8rem;
            color: #3f6b58;
        }
        @media (max-width: 700px) {
            .exam-container { padding: 18px; }
        }
    </style>
</head>
<body>
<div class="exam-container">
    <!-- الرأس: جامعة سوهاج + الصورة -->
    <div class="uni-header">
        <div class="uni-title">
            <h2>🌿 جامعة سوهاج - كلية العلوم</h2>
            <p>قسم النبات والميكروبيولوجي | الفرقة الأولى (لائحة موحدة) - شعبة العلوم البيولوجية والجيولوجية</p>
            <p><strong>المادة:</strong> فسيولوجيا النبات (BGS123) | <strong>التاريخ:</strong> 2025/5/31 | <strong>الزمن:</strong> 119 دقيقة</p>
        </div>
        <div class="profile-area">
            <img class="profile-img" src="https://photos.app.goo.gl/PiyJt63m43vwBADR8" alt="صورة الأستاذ" onerror="this.src='https://via.placeholder.com/65?text=Botany'; this.onerror=null;">
            <span>د. شيرين عبد المحسن</span>
        </div>
    </div>

    <div class="exam-meta">
        <span>📌 الدرجة الكلية: 120 درجة (70 + 30 + 20)</span>
        <span>✍️ أجب ثم اضغط "تحقق" لكل سؤال لمعرفة الصحة</span>
    </div>

    <!-- ========================= السؤال الأول ========================= -->
    <div class="section-title">📖 السؤال الأول: اختر الإجابة الصحيحة (10 × 7 = 70 درجة)</div>
    <div id="mcq-area"></div>

    <!-- ========================= السؤال الثاني ========================= -->
    <div class="section-title">✅❌ السؤال الثاني: صح وخطأ (15 × 2 = 30 درجة)</div>
    <div id="tf-area"></div>

    <!-- ========================= السؤال الثالث ========================= -->
    <div class="section-title">✍️ السؤال الثالث: أسئلة مقالية (20 درجة)</div>
    <div id="essay-area"></div>

    <footer>
        مع أطيب الأمنيات بالنجاح والتفوق 🌱 | امتحان تفاعلي - إجابات فورية ونماذج إجابة للأسئلة المقالية
    </footer>
</div>

<script>
    // ------------------------------------------------
    // الأسئلة حسب الورقة الأصلية (السؤال الأول اختياري)
    // ------------------------------------------------
    const mcqQuestions = [
        { text: "1- من الأسباب التي تؤدى إلى قلة نفاذية وامتصاص الماء في منطقة الاستطالة:", options: ["تغطى اسطحها بمادة هلامية", "غياب الأوعية الناقلة في انسجتها", "خلاياها ذات فجوة عصارية كبيرة"], correct: 1, explanation: "منطقة الاستطالة تفتقر إلى الأوعية الناقلة المتخصصة، كما أن خلاياها غير متمايزة لامتصاص الماء، بينما منطقة الشعيرات الجذرية هي المسؤولة عن الامتصاص." },
        { text: "2- تتم المرحلة الأولى في التنفس الهوائي للنباتات في ............", options: ["حشوة الميتوكوندريا", "الغشاء الداخلي للميتوكوندريا", "السيتوبلازم"], correct: 2, explanation: "المرحلة الأولى (تحلل السكر) تحدث في السيتوبلازم، ثم تنتقل后续 إلى الميتوكوندريا." },
        { text: "3- تحدث تفاعلات المرحلة الثانية للبناء الضوئي في", options: ["الثايلاكويد", "الستروما", "السيتوبلازم"], correct: 1, explanation: "تفاعلات الظلام (تثبيت الكربون) تحدث في ستروما البلاستيدات الخضراء." },
        { text: "4- إنزيم الكاتيكول أكسيديز من إنزيمات", options: ["النقل", "التحلل المائي", "الأكسدة والاختزال"], correct: 2, explanation: "هو إنزيم أكسدة (Oxidase) يساعد على أكسدة المركبات الفينولية." },
        { text: "5- من العوامل الداخلية التي تؤثر في سرعة النتح ............", options: ["النسبة بين المجموع الجذري والمجموع الخضري", "درجة الحرارة", "الرطوبة"], correct: 0, explanation: "النسبة بين الجذري والخضري عامل داخلي، أما الحرارة والرطوبة فهما خارجيان." },
        { text: "6- خاصية ....... هي حركة الجزيئات والدقائق من منطقة تركيز عالي إلى منطقة تركيز منخفض بفعل طاقتها الحركية.", options: ["التشرب", "الانتشار", "الأسموزية"], correct: 1, explanation: "الانتشار البسيط هو الحركة العشوائية مع تدرج التركيز." },
        { text: "7- محلول ...... يكون ضغطه الاسموزي أعلى من الضغط الاسموزي للخلية النباتية.", options: ["الفوقي (Hypertonic)", "المتساوى", "التحتي (Hypotonic)"], correct: 0, explanation: "المحلول فوق التوتر يسبب تحلل البلازما (plasmolysis)." },
        { text: "8- تعتبر منطقة .......... هي منطقة الامتصاص العظمي للماء في الجذور.", options: ["الاستطالة", "القمة النامية", "الشعيرات الجذرية"], correct: 2, explanation: "منطقة الشعيرات الجذرية تحتوي على خلايا بشرة ذات شعيرات تزيد من سطح الامتصاص." },
        { text: "9- يعتبر عنصر ......... من العناصر الغذائية الصغرى للنباتات.", options: ["البورون", "النيتروجين", "الكالسيوم"], correct: 0, explanation: "البورون من العناصر الصغرى، بينما النيتروجين والكالسيوم من العناصر الكبرى." },
        { text: "10- معامل التنفس يكون مساوياً للواحد عندما تكون المادة المستخدمة في عملية التنفس .......", options: ["أحماض عضوية", "دهون", "سكريات"], correct: 2, explanation: "معامل التنفس للكربوهيدرات = 1 (CO2/O2)." }
    ];

    // ------------------------------------------------
    // السؤال الثاني (صح/خطأ) 15 عبارة
    // ------------------------------------------------
    const tfStatements = [
        { text: "يتم ترسيب المحاليل الغروية الكارهة لوسط الانتشار على مرحلتين هما نزع الغلاف المائي ثم معادلة الشحنة.", isTrue: true },
        { text: "محلول احمر الفينول من المحاليل الغروية التي لها شحنة موجبة.", isTrue: false },
        { text: "يفضل النبات إمتصاص أيونات الفوسفات و هي في الوسط القاعدي.", isTrue: false },
        { text: "من مميزات المزارع المائية سهولة التحكم في كمية الهواء اللازمة لنمو الجذور.", isTrue: false },
        { text: "تعمل قوة التماسك لجزيئات الماء داخل أوعية الخشب على جعل عمود الماء معلق باستمرار في الوعاء الخشبي.", isTrue: true },
        { text: "من اعراض نقص البوتاسيوم موت الأطراف و عدم نمو الأجزاء الزهرية.", isTrue: true },
        { text: "ترجع أهمية الماغنسيوم في النبات إلى انه يدخل في تركيب جزيء الكلوروفيل.", isTrue: true },
        { text: "كمية الماء التي تنتقل خلال أوعية الخشب الربيعي تكون أقل من كمية الماء الذي ينتقل بواسطة الخشب الخريفي.", isTrue: false },
        { text: "درجة حرارة أعلى (ضمن الحدود المناسبة) تؤدي إلى زيادة سرعة امتصاص الماء لانخفاض لزوجة الماء.", isTrue: true },
        { text: "يدخل عنصر الكبريت في تركيب مركبات السيستين و الميثيونين.", isTrue: true },
        { text: "تتناسب سرعة النتح تناسباً طرديا مع المحتوى المائي للورقة النباتية.", isTrue: true },
        { text: "تحدث ظاهرة الإدماع عندما تكون الرطوبة النسبية منخفضة ودرجة الحرارة مرتفعة.", isTrue: false },
        { text: "يُظهر إنزيم اللاكتيك ديهيدروجينيز تخصص مطلق في عمله.", isTrue: false },
        { text: "الوظيفة الفسيولوجية للصوديوم أنه يعمل على اختزال النترات إلى نشادر.", isTrue: false },
        { text: "الأشجار لها ضغط اسموزي أعلى من الشجيرات.", isTrue: false },  // غير ثابتة، عادة متساوية أو حسب البيئة
        { text: "من شروط حدوث عملية التشرب، وجود قابلية للمادة كي تتشرب.", isTrue: true }
    ];
    // التأكد من 15 عبارة (المطلوب 15) وهي 16 عبارة، نقوم بأخذ أول 15 (حسب ورقة الامتحان المذكورة 15)
    const finalTF = tfStatements.slice(0, 15);

    // ------------------------------------------------
    // السؤال الثالث: أسئلة مقالية مع نموذج إجابة
    // ------------------------------------------------
    const essayQuestions = [
        { q: "1. اذكر العوامل التي تؤثر على عملية التنفس في النبات.", model: "تشمل: درجة الحرارة، تركيز الأكسجين، تركيز ثاني أكسيد الكربون، المادة المستعملة في التنفس (سكريات، دهون، بروتينات)، المحتوى المائي، الضوء (غير مباشر)، المواد الكيميائية (مثبطات)، عمر النسيج." },
        { q: "2. اذكر التخصص في الإنزيمات (أنواع التخصص الإنزيمي) مع الأمثلة.", model: "التخصص المطلق (مثل اليورياز)، التخصص في نوع الرابطة الكيميائية (مثل الليبيز يعمل على رابطة الإستر)، التخصص في البناء الفراغي (مثل اللاكتيك ديهيدروجينيز يعمل على اللاكتيك اليساري وليس اليميني)." },
        { q: "3. اذكر خواص المحاليل الغروية.", model: "الشحنة الكهربية (تنافر الدقائق)، الحركة البراونية، عدم الترسيب السهل (ثبات غروي)، خاصية التجمع السطحي (الأدمصاص)، النفاذية المحدودة عبر الأغشية شبه المنفذة، اللزوجة (تختلف حسب المحبة للماء أو الكراهية)." },
        { q: "4. اذكر العوامل التى تؤثر على الضغط الأسموزي للخلية النباتية.", model: "نوع النبات، عمر النسيج، مكان الخلية أو النسيج (القرب من مصدر الماء)، الأوقات المختلفة من اليوم أو السنة (التغيرات اليومية والموسمية)، العوامل البيئية (الضوء، الحرارة، الرطوبة)، تركيز العصير الخلوي." }
    ];

    // ---------- بناء أسئلة الاختيار من متعدد ----------
    function buildMCQ() {
        const container = document.getElementById('mcq-area');
        let html = '';
        mcqQuestions.forEach((q, idx) => {
            html += `
                <div class="question-card">
                    <div class="q-title">
                        <span class="q-num">سؤال ${idx+1}</span>
                        <span class="q-text">${q.text}</span>
                    </div>
                    <div class="options">
                        ${q.options.map((opt, optIdx) => `
                            <label class="option">
                                <input type="radio" name="mcq_${idx}" value="${optIdx}">
                                <span>${String.fromCharCode(65+optIdx)}- ${opt}</span>
                            </label>
                        `).join('')}
                    </div>
                    <button class="check-btn" data-type="mcq" data-idx="${idx}" data-correct="${q.correct}" data-exp="${q.explanation.replace(/"/g, '&quot;')}">✔ تحقق</button>
                    <div class="feedback" id="fb_mcq_${idx}"></div>
                </div>
            `;
        });
        container.innerHTML = html;
    }

    // ---------- بناء أسئلة صح/خطأ ----------
    function buildTF() {
        const container = document.getElementById('tf-area');
        let html = '';
        finalTF.forEach((item, idx) => {
            let correctVal = item.isTrue ? 'true' : 'false';
            html += `
                <div class="question-card">
                    <div class="q-title">
                        <span class="q-num">عبارة ${idx+1}</span>
                        <span class="q-text">${item.text}</span>
                    </div>
                    <div class="options">
                        <label class="option"><input type="radio" name="tf_${idx}" value="true"> ✔ صح (True)</label>
                        <label class="option"><input type="radio" name="tf_${idx}" value="false"> ✘ خطأ (False)</label>
                    </div>
                    <button class="check-btn" data-type="tf" data-idx="${idx}" data-correct="${correctVal}">📖 تحقق</button>
                    <div class="feedback" id="fb_tf_${idx}"></div>
                </div>
            `;
        });
        container.innerHTML = html;
    }

    // ---------- بناء الأسئلة المقالية مع إظهار الإجابة ----------
    function buildEssay() {
        const container = document.getElementById('essay-area');
        let html = '';
        essayQuestions.forEach((item, idx) => {
            html += `
                <div class="question-card">
                    <div class="q-title">
                        <span class="q-num">السؤال المقالي ${idx+1}</span>
                        <span class="q-text">${item.q}</span>
                    </div>
                    <button class="check-btn essay-btn" data-essay-idx="${idx}">📘 إظهار الإجابة النموذجية</button>
                    <div class="feedback" id="essay_answer_${idx}" style="display:none;"></div>
                </div>
            `;
        });
        container.innerHTML = html;
        // إضافة مستمعات لأزرار الإجابات المقالية
        document.querySelectorAll('.essay-btn').forEach(btn => {
            btn.addEventListener('click', (e) => {
                const idx = parseInt(btn.getAttribute('data-essay-idx'));
                const answerDiv = document.getElementById(`essay_answer_${idx}`);
                const modelText = essayQuestions[idx].model;
                answerDiv.style.display = 'block';
                answerDiv.innerHTML = `<div class="model-answer">✨ الإجابة النموذجية:<br> ${modelText}</div>`;
                btn.disabled = true;
                btn.textContent = '✓ تم عرض الإجابة';
            });
        });
    }

    // ---------- معالجة أحداث التحقق ----------
    function attachCheckEvents() {
        // يتم ربط الأحداث بعد بناء DOM
        const btns = document.querySelectorAll('.check-btn');
        btns.forEach(btn => {
            // تجنب ربط المقالي لاحقاً (لأن لها كلاس essay-btn مختلف)
            if (btn.classList.contains('essay-btn')) return;
            btn.addEventListener('click', (e) => {
                const type = btn.getAttribute('data-type');
                const idx = parseInt(btn.getAttribute('data-idx'));
                if (type === 'mcq') {
                    const radios = document.querySelectorAll(`input[name="mcq_${idx}"]`);
                    let selected = null;
                    for (let r of radios) if (r.checked) { selected = parseInt(r.value); break; }
                    const correctIdx = parseInt(btn.getAttribute('data-correct'));
                    const explanation = btn.getAttribute('data-exp') || '';
                    const fbDiv = document.getElementById(`fb_mcq_${idx}`);
                    if (selected === null) {
                        fbDiv.innerHTML = '<span class="feedback wrong-feedback">⚠️ يرجى اختيار إجابة أولاً</span>';
                        return;
                    }
                    if (selected === correctIdx) {
                        fbDiv.innerHTML = `<span class="feedback correct-feedback">✅ إجابة صحيحة! ${explanation ? '📘 ' + explanation : ''}</span>`;
                    } else {
                        const correctLetter = String.fromCharCode(65+correctIdx);
                        fbDiv.innerHTML = `<span class="feedback wrong-feedback">❌ إجابة خاطئة. الإجابة الصحيحة: ${correctLetter}. ${explanation ? '🔬 ' + explanation : ''}</span>`;
                    }
                } 
                else if (type === 'tf') {
                    const radios = document.querySelectorAll(`input[name="tf_${idx}"]`);
                    let selectedVal = null;
                    for (let r of radios) if (r.checked) { selectedVal = r.value; break; }
                    const correctBool = btn.getAttribute('data-correct') === 'true';
                    const fbDiv = document.getElementById(`fb_tf_${idx}`);
                    if (selectedVal === null) {
                        fbDiv.innerHTML = '<span class="feedback wrong-feedback">⚠️ اختر صح أو خطأ</span>';
                        return;
                    }
                    const userChoice = (selectedVal === 'true');
                    if (userChoice === correctBool) {
                        fbDiv.innerHTML = '<span class="feedback correct-feedback">✅ صحيح! العبارة سليمة.</span>';
                    } else {
                        fbDiv.innerHTML = `<span class="feedback wrong-feedback">❌ خطأ. الإجابة الصحيحة: ${correctBool ? 'صح' : 'خطأ'}. راجع المصدر.</span>`;
                    }
                }
            });
        });
    }

    // ---------- إعادة بناء الأحداث بعد تحميل المحتوى الديناميكي ----------
    function init() {
        buildMCQ();
        buildTF();
        buildEssay();
        attachCheckEvents();
    }
    init();
</script>
</body>
</html>
