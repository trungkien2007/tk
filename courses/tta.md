---
title: Các lớp Toán Tiếng Anh
layout: default
image: "/assets/img/dapp.png"
---

<style>
    .hero-section, .features-section, .quote-section, .blog-section {
        padding: 30px 0;
        border-radius: 2px;
    }
    
    .features-section * {
        box-sizing: border-box;
    }
    
    
    .features-section .feature-row {
        display: flex;
        justify-content: space-evenly;
        flex-wrap: wrap;
    }
    
    .features-section .feature-row .feature-card {
        background-color: #fff;
        /*width: 238.65px;*/
        width: calc(33.333% - 8px);
        margin-top: 16px;
        border-radius: 2px;
        box-shadow: 0 2px 2px 0 rgba(0,0,0,.14), 0 3px 1px -2px rgba(0,0,0,.2), 0 1px 5px 0 rgba(0,0,0,.12);
    }
    
    .features-section .feature-row .feature-card .image {
        background-color: rgb(43, 180, 201);
        background-size: cover;
        background-position: center;
        min-height: 4px;
    }
    
    .features-section .feature-row .feature-card .text {
        padding: 32px 16px;
    }
    
    .features-section h5 {
        color: #111;
        font-size: 21px;
    }
    
    .features-section p {
        color: #828282;
        font-size: 90%;
        padding-top: 12px;
        margin-bottom: 0;
    }

    .features-section .feature-row .feature-card.course:first-of-type {
        background-color: rgb(180, 43, 201);
    }

    .features-section .feature-row .feature-card.course:nth-of-type(2) {
        background-color: rgb(201,180,43);
    }

    .features-section .feature-row .feature-card.course:last-of-type {
        background-color: rgb(43,201,180);
    }

    .features-section .feature-row .feature-card.course .image {
        background-color: transparent;
    }

    .features-section .feature-row .feature-card.course .image h5 {
        background-color: #fff;
        color: rgb(201,180,43);
        position: relative;
        top: 4px;
        left: 2px;
        display: inline;
        padding: 6px 8px;
    }

    .features-section .feature-row .feature-card.course:first-of-type .image h5 {
        color: rgb(180, 43, 201);
    }

    .features-section .feature-row .feature-card.course:last-of-type .image h5 {
        color: rgb(43,201,180);
    }

    .features-section .feature-row .feature-card.course .text p {
        color: #f8f8f8;
    }

    .features-section .feature-row .feature-card.course .button a {
        color: #fff;
        border: 1px solid #f8f8f8;
        padding: 6px 16px;
    }
    .features-section .feature-row .feature-card.course .button a:visited {
        color: #fff;
    }
    .features-section .feature-row .feature-card.course .button a:hover {
        text-decoration: none;
        background-color: #fff;
        color: rgb(201,180,43);
    }
    .features-section .feature-row .feature-card.course:first-of-type .button a:hover {
        color: rgb(180, 43, 201);
    }

    .features-section .feature-row .feature-card.course:last-of-type .button a:hover {
        color: rgb(43,201,180);
    }

    .features-section .feature-row .feature-card.portrait .image {
        height: 192px;
        background-color: #333;
        position: relative;
    }

    .features-section .feature-row .feature-card.portrait .image h5 {
        color: #f8f8f8;
        background-color: rgb(43, 180, 201);
        display: inline-block;
        padding: 0 8px;
        position: absolute;
        bottom: -24px;
    }

    .features-section .feature-row .feature-card.portrait .text {
        padding: 8px 16px 28px;
    }
    
    .features-section .feature-row .feature-card .button {
        padding: 16px 16px 32px;
    }
    
    .quote-section {
        background-color: rgb(241, 241, 240);
        background-image: url("/assets/img/pattern1.png");
    }
    
    figure.testimonial {
        position: relative;
        float: left;
        margin: 10px 1% 40px;
        max-width: 480px;
        width: 100%;
        color: #333;
        text-align: left;
        border-radius: 90px;
        box-shadow: -3px 5px 12px 0 rgba(0,0,0,0.3);
    }
    figure.testimonial.first {
        transform: rotate(-5deg);
        top: 18px;
    }
    figure.testimonial.second {
        float:right;
        transform: rotate(15deg);
    }
    figure.testimonial * {
        -webkit-box-sizing: border-box;
        box-sizing: border-box;
    }
    figure.testimonial img {
        float: right;
        max-width: 40%;
        vertical-align: middle;
        background-color: rgb(107, 101, 91);
        /*border-radius: 0 8px 8px 0;*/
    }
    figure.testimonial figcaption {
        top: 0;
        bottom: 0;
        left: 0;
        width: 60%;
        position: absolute;
        background-color: #fdf9c5;
        border-radius: 8px 0 0 8px;
    }
    figure.testimonial blockquote {
        background-color: #fdf9c5;
        position: relative;
        padding: 25px 50px 25px 50px;
        font-size: 0.9em;
        font-weight: 500;
        text-align: left;
        margin: 0;
        line-height: 1.6em;
        font-style: italic;
        border-left: 0;
        color: #333;
    }
    figure.testimonial blockquote:before,
    figure.testimonial blockquote:after {
        font-family: 'FontAwesome';
        content: "\201C";
        position: absolute;
        font-size: 50px;
        opacity: 0.3;
        font-style: normal;
    }
    figure.testimonial blockquote:before {
        top: 25px;
        left: 20px;
    }
    figure.testimonial blockquote:after {
        content: "\201D";
        right: 20px;
        bottom: 0px;
    }
    figure.testimonial .arrow {
        top: 30px;
        left: 100%;
        width: 0;
        height: 0;
        border-left: 0 solid transparent;
        border-right: 25px solid transparent;
        border-top: 25px solid #fdf9c5;
        margin: 0;
        position: absolute;
    }
    figure.testimonial .author {
        position: absolute;
        top: 100%;
        width: 100%;
        padding: 10px 15px;
        color: #333;
        margin: 0;
        text-transform: uppercase;
    }
    figure.testimonial .author h5 {
        opacity: 0.8;
        margin: 0;
        font-weight: 800;
    }
    figure.testimonial .author h5 span {
        font-weight: 400;
        text-transform: none;
        padding-left: 5px;
    }
    
    @media only screen and (max-width: 700px) {
        .features-section .feature-row .feature-card {
            width: 48%;
        }
    }
    @media only screen and (max-width: 460px) {
        .features-section .feature-row .feature-card {
            width: 100%;
        }
        figure.testimonial.first {
            top: 32px;
        }
        figure.testimonial.first .author {
            top: auto;
            bottom: 100%;
        }
    }
    
    @media only screen and (max-width: 499px) {
        figure.testimonial img {
            display: none;
        }
        figure.testimonial figcaption {
            width: 100%;
            position: relative;
        }
        figure.testimonial.second {
            float:left;
        }
        figure.testimonial .arrow {
            display: none;
        }
        figure.testimonial.first blockquote {
            text-align: right;
        }
    }
    
    .hero-section {
        text-align: center;
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center;
        padding: 60px 4.5% 48px;
    }
    
    .hero-section h1 {
        font-size: 28px;
        font-weight: 500;
        color: #111;
    }
    
    .hero-section h3 {
        color: #333;
        font-weight: 300;
    }
    
    .hero-section .action-zone {
        padding: 32px 0;
    }
    
    .hero-section a.main-button {
        color: #f5f5f5;
        background-color: #15B5DD;
        text-decoration: none;
        padding: 16px 24px;
        border-radius: 2px;
    }
    
    .hero-section a.main-button:hover {
        color: #fff;
    }
    
    h2.section-title {
        font-weight: 300;
        text-transform: uppercase;
        text-align: center;
        color: #828282;
    }
</style>
<section class="hero-section">
    <div style="text-align: center;font-size:0.9rem;color:#333;font-weight:300">Khoá học</div>
    <h1>Toán Tiếng Anh</h1>
    <h3>Rèn luyện tư duy thực tiễn, kỹ năng ngôn ngữ hướng du học Mỹ</h3>
    <div class="action-zone">
        <a href="https://www.facebook.com/baphong80" class="main-button">ĐĂNG KÍ →</a>
    </div>
    <div>
        Liên hệ: <a href="mailto:baphong80@gmail.com" target="_blank">Email</a> - <a href="https://t.me/baphong" target="_blank">Telegram</a>
    </div>
</section>


<style>
    .key-info {
        list-style: none;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-evenly;
    }
    .key-info li {
        display: inline-block;
        padding: 18px 18px 3px;
        border-bottom: 2px solid #15B5DD;
        color: #15B5DD;
    }
    .blog-section {
        padding: 24px 18px 12px;
        margin-top: 2rem;
    }
    .blog-section h3 {
        text-transform: uppercase;
    }
    .blog-section ul {
        list-style: none; /* Remove default bullets */
    }

    .blog-section ul li::before {
        content: "\2022";  /* Add content: \2022 is the CSS Code/unicode for a bullet */
        color: #15B5DD; /* Change the color */
        font-weight: bold; /* If you want it to be bold */
        display: inline-block; /* Needed to add space between the bullet and the text */ 
        width: 1em; /* Also needed for space (tweak if needed) */
        margin-left: -1em; /* Also needed for space (tweak if needed) */
    }
</style>


<br><br>

<div class="blog-section" style="background:#eee">
    <h2 class="section-title">Lịch học</h2>
    <ul>
        <li>Lớp 1 lên 2, 2 lên 3: Thứ Tư, 17h30-19h15.</li>
        <li>Lớp 1 lên 2, 2 lên 3: Thứ Năm, 17h30-19h15.</li>
        <li>Lớp 1 lên 2, 2 lên 3: Thứ Sáu, 17h30-19h15,</li>
        <li>Lớp 3 lên 4, 4 lên 5: Thứ Hai, 17h30-19h15,</li>
        <li>Lớp 3 lên 4, 4 lên 5: Thứ Ba, 17h30-19h15,</li>
        <li>Lớp 5 lên 6, 6 lên 7: Thứ Hai, 19h30-21h15</li>
        <li>Lớp 5 lên 6, 6 lên 7: Thứ Năm, 19h30-21h15</li>
        <li>Lớp 7 lên 8, 8 lên 9: Thứ Ba, 19h30-21h15</li>
        <li>Lớp 7 lên 8, 8 lên 9: Thứ Tư, 19h30-21h15</li>
        <li>Lớp 10, 11, 12: Thứ Sáu, 19h30-21h15</li>
    </ul>
</div>

<div class="blog-section">
    <h2 class="section-title">10 khác biệt khi học với thầy Bá Phong</h2>
    <ul>
        <li>Không có vở ghi, vở nháp, không ghi bài, không có bút bi, bút mực, chỉ mang theo bút chì và tẩy.</li>
        <li>Không có bài tập về nhà, nhưng về nhà phải giảng lại bài đã học cho bố mẹ nghe và quay clip gửi thầy.</li>
        <li>Phương pháp học: tương tác, tranh biện, luyện tự duy.</li>
        <li>Giải lao được ngồi Thiền 10 phút hoặc xem clip Tiếng Anh, du học Mỹ. </li>
        <li>Toilet khép kín, sạch như ks 5 sao (HS bảo thế). </li>
        <li>Học thử 2 buổi, thấy phù hợp thì học lâu dài, chưa phù hợp thì nghỉ không đóng học phí.</li>
        <li>Thầy không kiểm tra đánh giá, các kỳ thi Toán Tiếng Anh quốc tế sẽ đánh giá cả thầy và trò.</li>
        <li>Học tốt, thi tốt thì đươc đi Singapore miễn phí vào dịp hè. </li>
        <li>Học Việt Nam nhưng đạt chuẩn Mỹ, có thể du học Mỹ ở bất kỳ cấp học nào. </li>
        <li>Giảm 50% học phí cho gia đình có hoàn cảnh khó khăn, mẹ đơn thân, gà trống nuôi con.</li>
    </ul>
    
</div>



<div class="hero-section">
    <h2 class="section-title">Đăng kí</h2>
    <div class="action-zone">
        <a href="https://www.facebook.com/baphong80" class="main-button">Facebook →</a>
    </div>
    <div>
        Liên hệ:  <a href="https://t.me/baphong" target="_blank">Telegram</a>
    </div>
</div>
