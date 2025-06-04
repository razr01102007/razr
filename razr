<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Тест по веб-разработке с иллюстрациями</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f5f7fa;
            color: #333;
        }

        h1 {
            color: #2c3e50;
            text-align: center;
            margin-bottom: 30px;
            padding-bottom: 10px;
            border-bottom: 2px solid #3498db;
        }

        .question {
            margin-bottom: 30px;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }

            .question:hover {
                transform: translateY(-3px);
            }

            .question p {
                font-weight: bold;
                margin-top: 0;
                color: #2c3e50;
                font-size: 18px;
            }

        .question-image {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
            margin: 10px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        label {
            display: flex;
            align-items: center;
            margin: 10px 0;
            cursor: pointer;
            padding: 10px;
            border-radius: 5px;
            transition: all 0.2s;
            background-color: #f8f9fa;
        }

            label:hover {
                background-color: #e9ecef;
                transform: translateX(5px);
            }

        input[type="radio"] {
            margin-right: 15px;
            transform: scale(1.2);
        }

        button {
            display: block;
            margin: 30px auto;
            background-color: #3498db;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            font-size: 18px;
            font-weight: bold;
            transition: all 0.3s;
            box-shadow: 0 3px 6px rgba(0,0,0,0.1);
        }

            button:hover {
                background-color: #2980b9;
                transform: translateY(-2px);
                box-shadow: 0 5px 10px rgba(0,0,0,0.2);
            }

        #result {
            margin-top: 30px;
            padding: 25px;
            text-align: center;
            font-size: 20px;
            font-weight: bold;
            border-radius: 10px;
            display: none;
            animation: fadeIn 0.5s ease-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .excellent {
            background-color: #d4edda;
            color: #155724;
            border-left: 5px solid #28a745;
        }

        .good {
            background-color: #fff3cd;
            color: #856404;
            border-left: 5px solid #ffc107;
        }

        .poor {
            background-color: #f8d7da;
            color: #721c24;
            border-left: 5px solid #dc3545;
        }

        .emoji {
            font-size: 24px;
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <h1>🌐 Тест по веб-разработке с иллюстрациями</h1>

    <div id="quiz">
        <div class="question">
            <p>1. Какой тег используется для создания заголовка первого уровня?</p>
            <img src="https://via.placeholder.com/600x200?text=HTML+Заголовки" alt="Пример заголовков" class="question-image">
            <label><input type="radio" name="q1" value="a"> &lt;head&gt; (используется для метаданных страницы)</label>
            <label><input type="radio" name="q1" value="b"> &lt;h1&gt; (правильный ответ)</label>
            <label><input type="radio" name="q1" value="c"> &lt;header&gt; (семантический тег для шапки сайта)</label>
        </div>

        <div class="question">
            <p>2. Какой атрибут HTML используется для определения альтернативного текста для изображения?</p>
            <img src="https://via.placeholder.com/600x200?text=Демонстрация+атрибутов+img" alt="Демонстрация атрибутов изображения" class="question-image">
            <label><input type="radio" name="q2" value="a"> src (указывает путь к изображению)</label>
            <label><input type="radio" name="q2" value="b"> link (не является атрибутом тега img)</label>
            <label><input type="radio" name="q2" value="c"> alt (правильный ответ - альтернативный текст)</label>
        </div>

        <div class="question">
            <p>3. Какой CSS-селектор выбирает элементы по идентификатору?</p>
            <img src="https://via.placeholder.com/600x200?text=CSS+Селекторы" alt="Пример CSS селекторов" class="question-image">
            <label><input type="radio" name="q3" value="a"> .class (выбирает по классу)</label>
            <label><input type="radio" name="q3" value="b"> #id (правильный ответ - выбор по ID)</label>
            <label><input type="radio" name="q3" value="c"> tag (выбирает все элементы этого типа)</label>
        </div>

        <div class="question">
            <p>4. Какой тег используется для создания ненумерованного списка?</p>
            <img src="https://via.placeholder.com/600x200?text=HTML+Списки" alt="Пример HTML списков" class="question-image">
            <label><input type="radio" name="q4" value="a"> &lt;ol&gt; (нумерованный список)</label>
            <label><input type="radio" name="q4" value="b"> &lt;ul&gt; (правильный ответ - маркированный список)</label>
            <label><input type="radio" name="q4" value="c"> &lt;li&gt; (элемент списка, но не сам список)</label>
        </div>

        <div class="question">
            <p>5. Какой HTML5-тег используется для навигации по сайту?</p>
            <img src="https://via.placeholder.com/600x200?text=Навигация+сайта" alt="Пример навигации сайта" class="question-image">
            <label><input type="radio" name="q5" value="a"> &lt;div&gt; (универсальный контейнер)</label>
            <label><input type="radio" name="q5" value="b"> &lt;nav&gt; (правильный ответ - семантический тег навигации)</label>
            <label><input type="radio" name="q5" value="c"> &lt;menu&gt; (устаревший тег)</label>
        </div>

        <div class="question">
            <p>6. Какое CSS-свойство изменяет цвет текста?</p>
            <img src="https://via.placeholder.com/600x200?text=CSS+Цвета" alt="Пример изменения цвета текста" class="question-image">
            <label><input type="radio" name="q6" value="a"> text-color (не существует)</label>
            <label><input type="radio" name="q6" value="b"> font-color (не существует)</label>
            <label><input type="radio" name="q6" value="c"> color (правильный ответ)</label>
        </div>

        <div class="question">
            <p>7. Какой тег используется для вставки JavaScript в HTML-документ?</p>
            <img src="https://via.placeholder.com/600x200?text=JavaScript+в+HTML" alt="Вставка JavaScript в HTML" class="question-image">
            <label><input type="radio" name="q7" value="a"> &lt;js&gt; (не существует)</label>
            <label><input type="radio" name="q7" value="b"> &lt;script&gt; (правильный ответ)</label>
            <label><input type="radio" name="q7" value="c"> &lt;javascript&gt; (не существует)</label>
        </div>

        <div class="question">
            <p>8. Какой метод HTTP используется для отправки данных формы?</p>
            <img src="https://via.placeholder.com/600x200?text=HTTP+Методы" alt="HTTP методы GET и POST" class="question-image">
            <label><input type="radio" name="q8" value="a"> GET (для получения данных)</label>
            <label><input type="radio" name="q8" value="b"> POST (правильный ответ - для отправки данных)</label>
            <label><input type="radio" name="q8" value="c"> SEND (не существует)</label>
        </div>

        <div class="question">
            <p>9. Какой тег создает абзац в HTML?</p>
            <img src="https://via.placeholder.com/600x200?text=HTML+Абзацы" alt="Пример HTML абзацев" class="question-image">
            <label><input type="radio" name="q9" value="a"> &lt;abbr&gt; (для аббревиатур)</label>
            <label><input type="radio" name="q9" value="b"> &lt;para&gt; (не существует)</label>
            <label><input type="radio" name="q9" value="c"> &lt;p&gt; (правильный ответ)</label>
        </div>

        <div class="question">
            <p>10. Какое CSS-свойство делает элемент невидимым, но сохраняет место в разметке?</p>
            <img src="https://via.placeholder.com/600x200?text=CSS+Видимость" alt="Сравнение visibility и display" class="question-image">
            <label><input type="radio" name="q10" value="a"> display: none (полностью удаляет из потока)</label>
            <label><input type="radio" name="q10" value="b"> visibility: hidden (правильный ответ - сохраняет место)</label>
            <label><input type="radio" name="q10" value="c"> opacity: 0 (делает прозрачным, но остается кликабельным)</label>
        </div>
    </div>

    <button onclick="checkAnswers()">✅ Проверить ответы</button>
    <div id="result"></div>

    <script>
        function checkAnswers() {
            // Правильные ответы
            const correctAnswers = {
                q1: "b",
                q2: "c",
                q3: "b",
                q4: "b",
                q5: "b",
                q6: "c",
                q7: "b",
                q8: "b",
                q9: "c",
                q10: "b"
            };

            let score = 0;
            const totalQuestions = Object.keys(correctAnswers).length;

            // Проверяем каждый вопрос
            for (const question in correctAnswers) {
                const selectedOption = document.querySelector(`input[name="${question}"]:checked`);

                if (selectedOption && selectedOption.value === correctAnswers[question]) {
                    score++;
                    // Добавляем визуальное подтверждение правильного ответа
                    selectedOption.parentElement.style.backgroundColor = "#d4edda";
                } else if (selectedOption) {
                    // Помечаем неправильные ответы
                    selectedOption.parentElement.style.backgroundColor = "#f8d7da";
                }
            }

            // Вычисляем процент правильных ответов
            const percentage = Math.round((score / totalQuestions) * 100);

            // Формируем сообщение с результатом
            let message = '';
            let resultClass = "";
            let emoji = "";

            if (percentage >= 80) {
                emoji = "🎉";
                message = `${emoji} Поздравляем! Вы ответили правильно на ${score} из ${totalQuestions} вопросов (${percentage}%). Отличный результат! Вы хорошо разбираетесь в веб-разработке.`;
                resultClass = "excellent";
            } else if (percentage >= 50) {
                emoji = "👍";
                message = `${emoji} Вы ответили правильно на ${score} из ${totalQuestions} вопросов (${percentage}%). Неплохо, но есть куда расти!`;
                resultClass = "good";
            } else {
                emoji = "💪";
                message = `${emoji} Вы ответили правильно на ${score} из ${totalQuestions} вопросов (${percentage}%). Попробуйте изучить материалы еще раз и пройти тест заново.`;
                resultClass = "poor";
            }

            // Выводим результат
            const resultElement = document.getElementById("result");
            resultElement.innerHTML = message;
            resultElement.className = resultClass;
            resultElement.style.display = "block";

            // Прокручиваем страницу к результату
            resultElement.scrollIntoView({ behavior: 'smooth' });
        }
    </script>
</body>
</html>
