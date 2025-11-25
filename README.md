/* فایل: style.css */

/* تنظیمات پایه و فارسی‌سازی (RTL) */
body {
    font-family: Tahoma, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
    direction: rtl; /* راست به چپ */
    text-align: right;
}

a {
    text-decoration: none;
    color: #007bff;
}

/* استایل عمومی بخش‌ها */
.content-section {
    padding: 60px 5%;
    margin: 0 auto;
    max-width: 1200px;
    text-align: center;
}

.secondary-bg {
    background-color: #e9ecef;
}

h1, h2 {
    color: #212529;
    margin-bottom: 20px;
}

/* بخش ۱: سربرگ */
.section-header {
    background-color: #343a40;
    color: white;
    padding: 80px 5%;
    text-align: center;
}

.section-header h1 {
    color: white;
    font-size: 2.5em;
}

.section-header p {
    font-size: 1.2em;
    opacity: 0.9;
}

/* بخش ۲: گرید محصولات */
.product-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin-top: 30px;
}

.product-card {
    background: white;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
    text-align: center;
}

.product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.15);
}

.product-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
    border-radius: 4px;
    margin-bottom: 15px;
    background-color: #eee; /* Placeholder background */
}

.product-card h3 {
    font-size: 1.3em;
    margin-bottom: 10px;
}

.price {
    color: #dc3545;
    font-size: 1.2em;
    font-weight: bold;
    margin-bottom: 15px;
}

.buy-button {
    display: inline-block;
    background-color: #28a745;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    font-weight: bold;
}

.buy-button:hover {
    background-color: #218838;
}

/* بخش ۴: دکمه واتساپ */
.whatsapp-button {
    display: inline-block;
    background-color: #25D366; /* رنگ سبز واتساپ */
    color: white;
    padding: 15px 30px;
    border-radius: 50px;
    font-size: 1.1em;
    font-weight: bold;
    margin-top: 10px;
    border: none;
    cursor: pointer;
    transition: background-color 0.3s;
}

.whatsapp-button:hover {
    background-color: #128C7E;
}

/* فوتر */
footer {
    text-align: center;
    padding: 20px;
    background-color: #343a40;
    color: #adb5bd;
    margin-top: 40px;
}
