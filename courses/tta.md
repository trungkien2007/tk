---
title: Các vấn đề nan giải của giới trẻ
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
    <div style="text-align: center;font-size:0.9rem;color:#333;font-weight:300">Các vấn đề</div>
    <h1>HẾT SỨC NAN GIẢI</h1>
    <h3>của giới trẻ hiện nay</h3>
    <div class="action-zone">
        <a href="https://www.facebook.com/baphong80" class="main-button">TÌM HIỂU THÊM →</a>
    </div>
    <div>
        Liên hệ: <a href="mailto:binbon0104@gmail.com" target="_blank">Email</a> - <a href="https://t.me/baphong" target="_blank">Telegram</a>
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
    <h2 class="section-title">Các vấn đề nan giải như sau:</h2>
    <ul>
        <li>Thích chạy theo giá trị ảo:Sự phát triển của công nghệ thông tin đặc biệt là internet đã có những tác động làm thay đổi cách nghĩ, thậm chí hành vi của giới trẻ. Nhiều bạn trẻ chạy theo những giá trị ảo – những giá trị không có thực ảnh hưởng lớn đến kinh tế, sức khoẻ, tinh thần và sự phát triển hoàn thiện nhân cách.

Cuộc sống online đã khiến nhiều bạn trẻ cổ xúy cho ngôn ngữ chat. Nhiều bạn trẻ đã biến những ngôn ngữ chát thành những mật mã mà người lớn, các bậc phụ huynh không thể nào dịch nổi. Hệ luỵ của nó không chỉ làm đau đầu các bậc phụ huynh mà một số từ ngữ được sử dụng tràn lan trong nhà trường làm đau đầu thầy, cô giáo và ảnh hưởng lớn đến sự trong sáng của tiếng Việt. Một số từ còn bị lạm dụng quá mức làm sai lệch so với nghĩa ban đầu, chẳng hạn như từ “tự kỷ”. Ở nhà không đi chơi - tự kỷ; ít ra ngoài - tự kỷ; không có người yêu - tự kỷ v.v….
Việc chạy theo những giá trị ảo cũng làm cho nhiều bạn trẻ trở nên nghiện games online, nghiện chát, nghiện facebooks dẫn đến những hệ luỵ khôn lường về thể chất và tinh thần. Bắt trước cuộc sống ảo trong các trò chơi khiến nhiều học sinh phạm phải những trọng tội trong đó có cả giết người.

Chính việc chạy theo những giá trị ảo là một trong những nguyên nhân khiến tỷ lệ phá thai ở Việt Nam thuộc top đầu thế giới. Do bắt chước những lối sống, trào lưu trên các trang báo mạng “lá cải” mà nhiều người nghĩ, có người yêu là sành điệu, cho rằng mình đã trưởng thành và nhiều trải nghiệm hơn người khác khi “yêu gấp”, “sống thử”. Bên cạnh đó, sự né tránh các vấn đề giới tính, sức khoẻ sinh sản của nền giáo dục nước nhà đã đẩy học sinh đến những hệ luỵ đáng buồn. Giáo viên dạy cho học sinh những điều mơ hồ về giới tính, tình dục, sức khoẻ sinh sản. Họ né tránh, tạo sự tò mò khiến học sinh phải tự tìm hiểu ở những nguồn khác, qua bạn bè, film ảnh… Sự tò mò cùng những kiến thức không đầy đủ về giới tính, sức khoẻ sinh sản, sức khoẻ tình dục khiến nhiều học sinh không biết tác hại của việc phá thai sẽ ảnh hưởng thế nào đến sức khỏe. Do đó, tỷ lệ nạo phá thái ở Việt Nam vẫn tiếp tục gia tăng. Người ta cứ sợ vẽ đường cho hươu chạy, nhưng có lẽ nên vẽ đường cho hươu chạy đúng hướng sẽ tốt hơn rất nhiều khi để hươu chạy tứ tán..</li>
        <li>khả năng tư duy độc lập hạn chế: Khả năng tư duy độc lập của giới trẻ hạn chế chủ yếu là do phương pháp giáo dục lạc hậu của Việt Nam tồn tại bấy lâu. Nếu như ở nước ngoài, giáo viên có thể đưa một cuốn sách, giao hẹn một tuần đọc xong, sau khi đọc xong học sinh/sinh viên sẽ viết một bài luận nêu quan điểm và nhận xét về cuốn sách vừa đọc sau đó, cả lớp cùng thảo luận. Thông thường, giáo viên giảng rất ít, chủ yếu cho học sinh ngồi từng nhóm thảo luận, phát biểu ý kiến, phân tích, nhận xét, bình luận… Giáo viên có vai trò là người hướng dẫn, định hướng, củng cố, đặt câu hỏi, đôi khi tranh luận, duy trì không khí thảo luận….Trong khi giáo dục Việt Nam chủ yếu theo hướng thụ động, giáo viên chủ yếu dùng phương pháp thuyết giảng, giảng giải, học sinh chủ yếu nghe, tiếp thu mà không có hoặc rất ít thảo luận, tranh luận. Cách dạy và học này được áp dụng trong suốt 12 năm phổ thong cho đến khi học đại học cách dạy và học này vẫn tồn tại làm cho học sinh/sinh viên mất đi khả năng phát biểu, đưa ra quan điểm của chính mình cho nên khả năng tư duy độc lập của họ rất hạn chế, thậm chí không có khẳ năng tư duy độc lập..</li>
        <li>Bệnh vô cảm: “Bệnh vô cảm” của giới trẻ trong xã hội hiện nay đang là thách đố cho các nhà giáo dục, các bậc cha mẹ, cũng như những người có trách nhiệm. “Bệnh vô cảm” được hiểu là một trạng thái tinh thần mà ở đó, con người không nảy sinh những cảm xúc đối với những sự vật, sự việc diễn ra xung quanh mình, những nỗi buồn, nỗi đau, sự mất mát, thiệt thòi của đồng loại. Những người sống vô cảm thường chỉ bo bo nghĩ đến lợi ích của riêng mình, ngại va chạm, sợ phiền toái, liên lụy với tâm niệm “đèn nhà ai nhà nấy rạng”. Những kẻ sống vô cảm thậm chí còn lạnh lùng, nhẫn tâm gieo rắc nỗi đau cho người khác mà không mảy may động lòng trắc ẩn. Đáng buồn là trong những vụ đánh nhau giữa các học sinh thời gian qua đều có một số đông “khán giả” trẻ tuổi, không chỉ thản nhiên đứng nhìn, mà còn dùng điện thoại di động ghi hình rồi tung lên mạng. Một biểu hiện nữa của thói vô cảm trong giới trẻ là sự chửi bới người lớn trong nhà, thái độ bàng quan với mọi việc xung quanh... của nhiều teen Việt. Gần đây, hàng loạt những câu chuyện teen dùng từ ngữ xúc phạm, hỗn xược với người lớn lan tràn trên facebooks đang gióng lên hồi chuông báo động về căn bệnh vô tâm của giới trẻ.

Một số học sinh, sinh viên mặc dù là những con mọt sách nhưng lại bàng quan với những gì xảy ra xung quanh mình. Họ không biết hiện nay ai là chủ tịch nước, ai là chủ tịch quốc hội, ai đang là thủ tướng. Chuyện thật như bịa nhưng đó là sự thực! Phải chăng nền giáo dục quá nặng nề…. khiến họ chỉ dành phần lớn thời gian chúi mũi vào bài vở và chạy theo điểm số và thứ hạng.
Bệnh vô cảm có những tác hại thật ghê gớm, nó không chỉ làm suy giảm đạo đức của một cá nhân mà còn đẩy đất nước đến bờ tụt hậu, suy thoái. Hãy thử tưởng tượng nếu đa số thế hệ trẻ có thái độ vô cảm thì tương lai của đất nước sẽ đi về đâu? Rường cột nước nhà sẽ ra sao, nếu không nói là đã mục nát ngay từ trong trứng nước? Quả thật, đó là một mối họa vô cùng lớn cho xã hội!</li>
        
    


<div class="blog-section">
    
   
    
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
