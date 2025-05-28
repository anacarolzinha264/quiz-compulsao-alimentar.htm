<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Quiz: Mitos e Fatos sobre Compulsão Alimentar</title>
<style>
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: linear-gradient(135deg, #f0f4f8, #d9e2ec);
    color: #102a43;
    margin: 0;
    padding: 1.5rem;
  }
  h1 {
    text-align: center;
    color: #334e68;
    margin-bottom: 2rem;
  }
  .quiz-container {
    max-width: 700px;
    margin: 0 auto;
    background: #fff;
    border-radius: 12px;
    padding: 2rem 3rem;
    box-shadow: 0 6px 15px rgba(14, 48, 80, 0.15);
  }
  .question {
    font-size: 1.2rem;
    margin-bottom: 1rem;
    font-weight: 600;
  }
  .options label {
    display: block;
    background: #e1e8f0;
    margin-bottom: 0.7rem;
    padding: 0.8rem 1rem;
    border-radius: 8px;
    cursor: pointer;
    transition: background 0.3s ease;
    user-select: none;
  }
  .options input[type="radio"] {
    display: none;
  }
  .options input[type="radio"]:checked + label {
    background: #627d98;
    color: #fff;
  }
  button {
    display: block;
    margin: 2rem auto 0 auto;
    background: #334e68;
    color: #fff;
    border: none;
    padding: 0.9rem 2.5rem;
    font-size: 1rem;
    border-radius: 25px;
    cursor: pointer;
    box-shadow: 0 4px 10px rgba(51, 78, 104, 0.4);
    transition: background 0.3s ease;
  }
  button:hover {
    background: #526d82;
  }
  #result {
    margin-top: 2rem;
    font-size: 1.2rem;
    font-weight: 700;
    color: #243b53;
    text-align: center;
  }
  .correct {
    color: #2a9d8f;
    font-weight: 700;
  }
  .incorrect {
    color: #e76f51;
    font-weight: 700;
  }
  .explanation {
    font-size: 0.9rem;
    margin: 0.3rem 0 1rem 0;
    color: #486581;
  }
</style>
</head>
<body>
  <h1>Quiz: Mitos e Fatos sobre Compulsão Alimentar</h1>
  <div class="quiz-container" id="quiz">

    <!-- Perguntas do quiz geradas dinamicamente pelo JS -->

  </div>
  <script>
    const quizData = [
      {
        question: "A compulsão alimentar é apenas falta de força de vontade para controlar a alimentação.",
        options: ["Mito", "Fato"],
        correct: 0,
        explanation: "A compulsão alimentar é um transtorno complexo que envolve fatores emocionais, biológicos e sociais, e não apenas uma questão de força de vontade."
      },
      {
        question: "Pessoas com compulsão alimentar frequentemente comem grandes quantidades de comida em um curto período de tempo, mesmo sem fome.",
        options: ["Mito", "Fato"],
        correct: 1,
        explanation: "Este é um dos principais critérios para o diagnóstico da compulsão alimentar."
      },
      {
        question: "Compulsão alimentar afeta somente pessoas com sobrepeso ou obesidade.",
        options: ["Mito", "Fato"],
        correct: 0,
        explanation: "A compulsão alimentar pode afetar indivíduos de qualquer peso, incluindo aqueles com peso normal."
      },
      {
        question: "Tratar compulsão alimentar envolve apenas modificar hábitos alimentares.",
        options: ["Mito", "Fato"],
        correct: 0,
        explanation: "O tratamento eficaz deve envolver abordagens psicológicas, nutricionais e, em alguns casos, médicas, por isso é interprofissional."
      },
      {
        question: "Estresse e emoções negativas podem ser gatilhos para episódios de compulsão alimentar.",
        options: ["Mito", "Fato"],
        correct: 1,
        explanation: "Muitas pessoas apresentam episódios de compulsão associados a emoções negativas e estresse."
      },
      {
        question: "A compulsão alimentar não é um problema sério e tende a desaparecer sem tratamento.",
        options: ["Mito", "Fato"],
        correct: 0,
        explanation: "A compulsão alimentar pode causar sofrimento significativo e impacto na saúde e frequentemente precisa de suporte profissional."
      }
    ];

    const quizContainer = document.getElementById("quiz");
    let currentAnswers = [];

    function buildQuiz() {
      const output = quizData.map((item, index) => {
        const optionsHtml = item.options.map((option, i) => 
          `<input type="radio" id="q${index}o${i}" name="question${index}" value="${i}" />
          <label for="q${index}o${i}">${option}</label>`).join("");
        return `<div class="question-block">
          <p class="question">${index + 1}. ${item.question}</p>
          <div class="options">${optionsHtml}</div>
          <div class="explanation" id="explanation${index}" style="display: none;"></div>
          <hr />
        </div>`
      }).join("");
      quizContainer.innerHTML = output + `<button id="submitBtn">Verificar Respostas</button><div id="result"></div>`;
    }

    function showResults() {
      let score = 0;
      quizData.forEach((item, index) => {
        const selected = document.querySelector(`input[name="question${index}"]:checked`);
        const explanationEl = document.getElementById(`explanation${index}`);
        if (!selected) {
          explanationEl.style.display = "block";
          explanationEl.textContent = "Você não respondeu essa pergunta.";
          explanationEl.className = "explanation incorrect";
        } else {
          const answer = parseInt(selected.value);
          if(answer === item.correct) {
            score++;
            explanationEl.textContent = "Resposta Correta! " + item.explanation;
            explanationEl.className = "explanation correct";
          } else {
            explanationEl.textContent = "Resposta Incorreta. " + item.explanation;
            explanationEl.className = "explanation incorrect";
          }
          explanationEl.style.display = "block";
        }
      });
      const resultEl = document.getElementById("result");
      resultEl.textContent = `Você acertou ${score} de ${quizData.length} perguntas.`;
    }

    buildQuiz();
    quizContainer.addEventListener('click', function(e) {
      if(e.target && e.target.id === 'submitBtn') {
        showResults();
        e.target.disabled = true;
      }
    });
  </script>
</body>
</html>
