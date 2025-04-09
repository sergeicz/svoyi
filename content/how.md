---
title: "Как мы сделали этот сайт"
date: 2025-04-09
draft: false
---

<body>
    <h1>Как мы сделали этот сайт</h1>
    <p>Создание сайта с нуля всегда требует множества решений, но наша задача была немного сложнее. Мы решили отказаться от традиционных CMS с базой данных, что позволило нам повысить безопасность и скорость загрузки сайта. Обычные CMS могут быть подвержены взломам, и они требуют больше серверных ресурсов для обработки запросов. В нашем случае это было бы излишним. Мы сосредоточились на статическом генераторе сайтов, который не только улучшает производительность, но и значительно снижает затраты на обслуживание.</p>

    <h2>Что использовалось для создания сайта</h2>
    <p>Наша цель состояла в том, чтобы создать удобный и эффективный сайт, который будет быстро загружаться и требовать минимальных затрат на обслуживание. Для этого мы выбрали следующие инструменты:</p>

    <h3>Использованные инструменты:</h3>
    <a href="https://gohugo.io/" target="_blank" style="display: inline-block; margin-right: 10px;">
        <img src="https://www.gohugothemes.com/images/logo/logo.png" alt="Hugo" style="width: 30px; height: 30px;">
    </a>
    <a href="https://github.com/" target="_blank" style="display: inline-block; margin-right: 10px;">
        <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" style="width: 30px; height: 30px;">
    </a>
    <a href="https://www.netlify.com/" target="_blank" style="display: inline-block; margin-right: 10px;">
        <img src="https://www.netlify.com/img/global/logo.svg" alt="Netlify" style="width: 30px; height: 30px;">
    </a>
    <a href="https://www.cloudflare.com/" target="_blank" style="display: inline-block;">
        <img src="https://www.cloudflare.com/img/cf-logo.svg" alt="Cloudflare" style="width: 30px; height: 30px;">
    </a>

    <h2>Процесс разработки</h2>
    <p>Для генерации статического сайта мы использовали <strong>Hugo</strong> — мощный генератор, который позволяет быстро создавать сайты без необходимости в серверной базе данных. Этот инструмент создает сайт на основе контента, написанного в Markdown, и шаблонов HTML, что позволяет нам избежать нагрузки от динамической генерации страниц. В результате сайт работает быстрее и более безопасно, так как нет необходимости обрабатывать запросы к базе данных.</p>

    <p>Далее, для размещения сайта в интернете мы использовали <strong>Netlify</strong>. Этот сервис позволяет очень легко деплоить статические сайты, автоматизировать процессы обновления контента и настраивать интеграцию с GitHub для автоматического деплоя при каждом пуше в репозиторий. Netlify также предлагает бесплатный SSL-сертификат, что добавляет дополнительный уровень безопасности.</p>

    <p>Для управления DNS и защиты сайта мы использовали <strong>Cloudflare</strong>. Этот сервис обеспечивает защиту от DDoS-атак, а также помогает ускорить доставку контента с помощью их CDN. В результате сайт становится доступен по всему миру с минимальной задержкой.</p>

    <h2>Что это дает</h2>
    <p>Все эти решения позволили нам отказаться от сложных и дорогих решений для сайтов на базе CMS. Статический сайт работает быстрее, а его содержание проще поддерживать. Каждое обновление контента занимает всего несколько минут и не требует дополнительной нагрузки на сервер. Этот подход позволяет минимизировать затраты на хостинг и обслуживание, а также повысить безопасность.</p>

    <h2>Деплой и автоматизация</h2>
    <p>Для деплоя мы используем GitHub в связке с Netlify. Как только мы вносим изменения в репозиторий, Netlify автоматически обновляет сайт. Это позволяет нам легко контролировать изменения и быстро откатывать их, если что-то пошло не так. Весь процесс автоматизирован, что экономит нам время и ресурсы.</p>

    <h2>Заключение</h2>

        <!-- Иконки инструментов внизу страницы -->
    <section class="tools-section">
        <h3>Инструменты, которые мы использовали:</h3>
        <a href="https://gohugo.io/" target="_blank" style="display: inline-block; margin-right: 10px;">
            <img src="https://raw.githubusercontent.com/gohugoio/hugo/master/images/hugo-logo.png" alt="Hugo" style="width: 30px; height: 30px;">
        </a>
        <a href="https://github.com/" target="_blank" style="display: inline-block; margin-right: 10px;">
            <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" style="width: 30px; height: 30px;">
        </a>
        <a href="https://www.netlify.com/" target="_blank" style="display: inline-block; margin-right: 10px;">
            <img src="https://www.netlify.com/img/global/logo.svg" alt="Netlify" style="width: 30px; height: 30px;">
        </a>
        <a href="https://www.cloudflare.com/" target="_blank" style="display: inline-block;">
            <img src="https://www.cloudflare.com/img/cf-logo.svg" alt="Cloudflare" style="width: 30px; height: 30px;">
        </a>
    </section>
</body>
