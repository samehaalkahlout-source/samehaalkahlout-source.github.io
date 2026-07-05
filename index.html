<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>المنيو الإلكتروني الإبداعي</title>
    <style>
        :root {
            --bg-color: #0b0f14;
            --card-bg: #131922;
            --accent-color: #00d2c4;
            --text-main: #ffffff;
            --text-muted: #a0aec0;
            --border-color: #1e2633;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-main);
            padding-bottom: 90px;
        }

        /* القائمة العلوية للتنقل */
        .navbar {
            display: flex;
            overflow-x: auto;
            background-color: #070a0e;
            padding: 15px 10px;
            position: sticky;
            top: 0;
            z-index: 100;
            border-bottom: 1px solid var(--border-color);
            scrollbar-width: none;
        }
        .navbar::-webkit-scrollbar { display: none; }

        .nav-item {
            padding: 8px 16px;
            margin: 0 5px;
            border-radius: 20px;
            background-color: var(--card-bg);
            color: var(--text-muted);
            white-space: nowrap;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 14px;
            border: 1px solid var(--border-color);
        }
        .nav-item.active {
            background-color: var(--accent-color);
            color: #000;
            font-weight: bold;
        }

        /* عنوان القسم */
        .section-title {
            padding: 20px 15px 10px;
            font-size: 22px;
            color: var(--accent-color);
            font-weight: bold;
        }

        /* شبكة المنتجات */
        .menu-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 15px;
            padding: 15px;
        }
        @media(min-width: 768px) {
            .menu-grid { grid-template-columns: 1fr 1fr; }
        }

        /* كارت الوجبة */
        .menu-card {
            background-color: var(--card-bg);
            border-radius: 12px;
            padding: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border: 1px solid var(--border-color);
            position: relative;
        }

        .card-info {
            flex: 1;
            padding-left: 15px;
        }

        .card-title {
            font-size: 17px;
            font-weight: bold;
            margin-bottom: 6px;
        }

        .card-desc {
            font-size: 12px;
            color: var(--text-muted);
            margin-bottom: 12px;
            line-height: 1.4;
        }

        .price-select-container {
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .size-select {
            background: #1c2431;
            color: white;
            border: 1px solid var(--border-color);
            padding: 4px 8px;
            border-radius: 6px;
            font-size: 12px;
            outline: none;
        }

        .card-price {
            color: var(--accent-color);
            font-weight: bold;
            font-size: 16px;
        }

        .card-right {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .card-img {
            width: 85px;
            height: 85px;
            border-radius: 12px;
            object-fit: cover;
            border: 1px solid var(--border-color);
        }

        .add-btn {
            width: 32px;
            height: 32px;
            border-radius: 8px;
            background-color: transparent;
            border: 2px solid var(--accent-color);
            color: var(--accent-color);
            font-size: 20px;
            font-weight: bold;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.2s ease;
        }
        .add-btn:hover {
            background-color: var(--accent-color);
            color: #000;
        }

        /* شريط الطلب السفلي */
        .order-bar-container {
            position: fixed;
            bottom: 20px;
            left: 0;
            right: 0;
            display: flex;
            justify-content: center;
            padding: 0 20px;
            z-index: 99;
        }

        .order-bar {
            background: linear-gradient(135deg, #00d2c4, #00bfa5);
            color: #000;
            padding: 15px 30px;
            border-radius: 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 100%;
            max-width: 500px;
            box-shadow: 0 10px 25px rgba(0, 210, 196, 0.3);
            font-weight: bold;
            cursor: pointer;
        }

        .order-count {
            background-color: #000;
            color: #fff;
            width: 24px;
            height: 24px;
            border-radius: 50px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 12px;
            margin-left: 10px;
        }
    </style>
</head>
<body>

    <div class="navbar" id="navbar"></div>

    <div class="section-title" id="sectionTitle"></div>

    <div class="menu-grid" id="menuGrid"></div>

    <div class="order-bar-container">
        <div class="order-bar" onclick="alert('تم إرسال طلبك بنجاح!')">
            <div style="display: flex; align-items: center;">
                <span class="order-count" id="cartCount">0</span>
                <span>استكمال الطلب</span>
            </div>
            <div id="cartTotal">0.00 ₪</div>
        </div>
    </div>

    <script>
        // هنا يمكنك التعديل وإضافة الأصناف والأسعار والصور بسهولة تامة!
        const menuData = {
            "المشاريب الباردة": [
                { name: "ايس كوفي", desc: "انتعاش القهوة الباردة الغنية بطعمها الأسطوري لضبط المزاج.", prices: { "وسط": 6, "كبير": 10 }, img: "https://images.unsplash.com/photo-1517701604599-bb29b565090c?w=300" },
                { name: "فيوزتي خوخ", desc: "شاي مثلج بنكهة الخوخ الطبيعية المنعشة.", prices: { "وسط": 6, "كبير": 10 }, img: "https://images.unsplash.com/photo-1497534446932-c925b458314e?w=300" },
                { name: "ايس فانيل", desc: "مزيج الفانيلا الباردة الناعمة لعشاق المذاق الهادئ.", prices: { "وسط": 6, "كبير": 10 }, img: "https://images.unsplash.com/photo-1572490122747-3968b75cc699?w=300" },
                { name: "تنر هندي", desc: "المشروب البارد العريق بنكهته الأصلية المميزة.", prices: { "وسط": 6, "كبير": 10 }, img: "https://images.unsplash.com/photo-1541658016709-82535e94bc69?w=300" },
                { name: "ايس بسفلوره", desc: "طعم الباشن فروت الاستوائي الفريد يأخذك لعالم آخر.", prices: { "وسط": 6, "كبير": 10 }, img: "https://images.unsplash.com/photo-1534353436294-0dbd4bdac845?w=300" },
                { name: "ايس كرز", desc: "كرز أحمر مثلج يعطيك طاقة وانتعاش لا ينتهي.", prices: { "وسط": 6, "كبير": 10 }, img: "https://images.unsplash.com/photo-1527661591475-527312dd65f5?w=300" },
                { name: "ايس مانجا", desc: "قطع المانجو الطبيعية محفوفة بالثلج المجروش.", prices: { "وسط": 6, "كبير": 10 }, img: "https://images.unsplash.com/photo-1553530666-ba11a7da3888?w=300" },
                { name: "ايس اناناس", desc: "عصير الأناناس البارد المنعش، حلاوة خفيفة وانتعاش قوي.", prices: { "وسط": 6, "كبير": 10 }, img: "https://images.unsplash.com/photo-1621263764928-df1444c5e859?w=300" },
                { name: "ايس يوجورت فراوله", desc: "الزبادي البارد المخفوق مع الفراولة الطازجة لذة لا تقاوم.", prices: { "وسط": 6, "كبير": 10 }, img: "https://images.unsplash.com/photo-1563805042-7684c019e1cb?w=300" },
                { name: "ايس موز", desc: "الموز الغني بالفوائد بنكهة مثلجة وكريمية ممتازة.", prices: { "وسط": 6, "كبير": 10 }, img: "https://images.unsplash.com/photo-1528825871115-3581a5387919?w=300" }
            ],
            "موهيتو": [
                { name: "موهيتو كلاسيك", desc: "النعناع الطازج مع الليمون الحامض والصودا الباردة.", prices: { "عادي": 10 }, img: "https://images.unsplash.com/photo-1513558161293-cdaf765ed2fd?w=300" },
                { name: "ترند مثلجات هايدي", desc: "الخلطة السرية الترند التي يبحث عنها الجميع بطعم أسطوري.", prices: { "عادي": 10 }, img: "https://images.unsplash.com/photo-1488900128323-21503983a07e?w=300" },
                { name: "كوكتيلات الموهيتو", desc: "تشكيلة من الفواكه المشكلة المدموجة مع انتعاش الموهيتو الخاص.", prices: { "عادي": 10 }, img: "https://images.unsplash.com/photo-1546173152-318e72403613?w=300" }
            ],
            "وجبات بحرية": [
                { name: "جمبري 8 قطع", desc: "٨ قطع جمبري مقرمش ومبهر يقدم مع بطاطس شيبس ذهبية وصوص.", prices: { "وجبة": 35 }, img: "https://images.unsplash.com/photo-1565557623262-b51c2513a641?w=300" },
                { name: "وجبة 10 قطع", desc: "١٠ قطع من الجمبري الجامبو الفاخر مقلي بعناية مع الشيبس المقرمش.", prices: { "وجبة": 40 }, img: "https://images.unsplash.com/photo-1625938146369-adc83368bda7?w=300" },
                { name: "وجبة 12 قطعة", desc: "الوليمة الكبرى! ١٢ قطعة جمبري شهية لعشاق القرمشة البحرية مع الشيبس.", prices: { "وجبة": 50 }, img: "https://images.unsplash.com/photo-1534422298391-e4f8c172dddb?w=300" }
            ],
            "الحلويات": [
                { name: "أصابع وافل فانيل نوتيلا", desc: "أصابع الوافل المقرمشة والدافئة مغطاة بشوكولاتة النوتيلا الفاخرة.", prices: { "حبة": 5 }, img: "https://images.unsplash.com/photo-1562376502-6f769499c886?w=300" },
                { name: "أصابع وافل فانيل لوتوس", desc: "طعم بسكويت اللوتوس البلجيكي الشهير يذوب فوق وافل الفانيلا الساخن.", prices: { "حبة": 5 }, img: "https://images.unsplash.com/photo-1587314168485-3236d6710814?w=300" },
                { name: "أصابع وافل نوتيلا لوتوس بستاشيو", desc: "المزيج الثلاثي الخارق! نوتيلا، لوتوس، وزبدة الفستق الحلبي الفاخرة.", prices: { "حبة": 7 }, img: "https://images.unsplash.com/photo-1551024601-bec78aea704b?w=300" },
                { name: "أصابع وافل بستاشيو", desc: "وافل غني بصوص البستاشيو (الفستق الحلبي) الأصلي لعشاق المذاق المميز.", prices: { "حبة": 7 }, img: "https://images.unsplash.com/photo-1571877227200-a0d98ea607e9?w=300" }
            ],
            "وجبات ذرة": [
                { name: "ذرة عالبخار (وسط)", desc: "كاسة ذرة حلوة مطهوة على البخار مع الزبدة والبهارات الخاصة.", prices: { "وسط": 7 }, img: "https://images.unsplash.com/photo-1601004890684-d8cbf643f5f2?w=300" },
                { name: "ذرة عالبخار (كبير)", desc: "كاسة بحجم كبير مشبعة ومثالية للأوقات الجميلة بالزبدة والليمون.", prices: { "كبير": 10 }, img: "https://images.unsplash.com/photo-1551782450-17144efb9c50?w=300" },
                { name: "صحن ذرة كبير", desc: "مشاركة اللذة! صحن عائلي كبير من الذرة بالبخار والخلطة السرية.", prices: { "صحن": 20 }, img: "https://images.unsplash.com/photo-1514516345957-556ca7d90a29?w=300" }
            ]
        };

        let currentSection = Object.keys(menuData)[0];
        let cart = [];

        function renderNavbar() {
            const navbar = document.getElementById('navbar');
            navbar.innerHTML = '';
            Object.keys(menuData).forEach((section, index) => {
                const item = document.createElement('div');
                item.className = `nav-item ${section === currentSection ? 'active' : ''}`;
                item.innerText = section;
                item.onclick = () => switchSection(section);
                navbar.appendChild(item);
            });
        }

        function switchSection(section) {
            currentSection = section;
            renderNavbar();
            renderMenu();
        }

        function renderMenu() {
            document.getElementById('sectionTitle').innerText = currentSection;
            const grid = document.getElementById('menuGrid');
            grid.innerHTML = '';

            menuData[currentSection].forEach((item, index) => {
                const card = document.createElement('div');
                card.className = 'menu-card';

                // تجهيز قائمة اختيار الحجم/السعر إذا كان هناك أكثر من سعر
                let priceKeys = Object.keys(item.prices);
                let priceHTML = '';
                let selectHTML = '';

                if (priceKeys.length > 1) {
                    selectHTML = `<select class="size-select" onchange="updatePrice(this, ${index})">`;
                    priceKeys.forEach(k => {
                        selectHTML += `<option value="${item.prices[k]}">${k}</option>`;
                    });
                    selectHTML += `</select>`;
                    priceHTML = `<span class="card-price" id="price-${index}">${item.prices[priceKeys[0]]} ₪</span>`;
                } else {
                    priceHTML = `<span class="card-price">${item.prices[priceKeys[0]]} ₪</span>`;
                }

                card.innerHTML = `
                    <div class="card-info">
                        <div class="card-title">${item.name}</div>
                        <div class="card-desc">${item.desc}</div>
                        <div class="price-select-container">
                            ${selectHTML}
                            ${priceHTML}
                        </div>
                    </div>
                    <div class="card-right">
                        <img class="card-img" src="${item.img}" alt="${item.name}">
                        <button class="add-btn" onclick="addToCart('${item.name}', ${index}, '${priceKeys.length > 1 ? 'selected' : priceKeys[0]}')">+</button>
                    </div>
                `;
                grid.appendChild(card);
            });
        }

        function updatePrice(selectEl, index) {
            document.getElementById(`price-${index}`).innerText = selectEl.value + " ₪";
        }

        function addToCart(name, index, sizeKey) {
            let price = 0;
            let item = menuData[currentSection][index];
            if (sizeKey === 'selected') {
                const grid = document.getElementById('menuGrid');
                const card = grid.children[index];
                const select = card.querySelector('.size-select');
                price = parseFloat(select.value);
            } else {
                price = item.prices[sizeKey];
            }

            cart.push({ name: name, price: price });
            updateCartUI();
        }

        function updateCartUI() {
            document.getElementById('cartCount').innerText = cart.length;
            let total = cart.reduce((sum, item) => sum + item.price, 0);
            document.getElementById('cartTotal').innerText = total.toFixed(2) + " ₪";
        }

        // تشغيل المنيو لأول مرة
        renderNavbar();
        renderMenu();
    </script>
</body>
</html>
