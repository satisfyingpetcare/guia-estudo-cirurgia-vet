# guia-estudo-cirurgia-vet
# 📚 Guia Definitivo: Cirurgia & Farmacologia Veterinária

---

## 1. Desinquinação e Preparação do Paciente

* **Conceito:** Processo de limpeza, debridamento e remoção de sujidades para prevenir Infecções de Sítio Cirúrgico (ISC).
* **Tricotomia:** Ampla na área cirúrgica, realizada imediatamente antes do procedimento (evita microlesões).
* **Degermação/Antissepsia:** 
  1. Lavagem mecânica com **Clorexidina Degermante 4%** do centro (linha de incisão) para a periferia.
  2. Aplicação de **Clorexidina Alcoólica 0,5%** de forma centrífuga (sem retornar ao centro).
* **Campo Cirúrgico:** Delimitação com 4 panos fixados na pele pelas **pinças de Backhaus**.

---

## 2. Paramentação e Assepsia da Equipe

* **Escovação das Mãos:**
  1. Unhas/região subungueal → faces laterais dos dedos → palmas e dorsos → antebraço (distal ao proximal).
  2. Manter sempre as **mãos acima do nível dos cotovelos** ao enxaguar.
  3. Secar com compresta estéril (um lado exclusivo para cada braço).
* **Técnica Fechada de Luvas:** As mãos permanecem dentro dos punhos do avental estéril enquanto vestem as luvas.

---

## 3. Instrumentos Cirúrgicos (Mesa de Mayo)

| Tempo Cirúrgico | Função | Instrumentos |
| :--- | :--- | :--- |
| **1. Diérese** | Incisão e corte | Cabo de bisturi nº 3, Tesouras de Metzenbaum e Mayo |
| **2. Hemostasia** | Oclusão de vasos | Pinças Halsted (Mosquito), Kelly e Crile |
| **3. Apreensão** | Manipulação | Pinças Adson com dente de rato, Adson-Brown e Allis |
| **4. Campo** | Fixação dos panos | Pinça de Backhaus |
| **5. Síntese** | Sutura | Porta-agulhas (Mayo-Hegar), Agulhas e Fios (Vicryl, Monocryl, Nylon) |

---

## 4. Guia Rápido de Cálculos de Doses

### Formulação Base
$$Volume (mL) = \frac{Peso (kg) \times Dose (mg/kg)}{Concentração (mg/mL)}$$

### Conversão de Porcentagem (%) para mg/mL
> **Regra de Ouro:** Multiplique a % por **10**.
> * Lidocaína 2% = 20 mg/mL
> * Acepran 0,2% = 2 mg/mL
> * Propofol 1% = 10 mg/mL

---

## 📝 Quiz de Fixação para a Prova

<div class="quiz-container">
  <p><strong>1. Qual o volume de Lidocaína 2% (20 mg/mL) para um bloqueio intratesticular em um cão de 10 kg na dose de 2 mg/kg?</strong></p>
  <label class="quiz-option"><input type="radio" name="q1" value="a"> A) 0,5 mL</label>
  <label class="quiz-option"><input type="radio" name="q1" value="b"> B) 1,0 mL total (0,5 mL por testículo)</label>
  <label class="quiz-option"><input type="radio" name="q1" value="c"> C) 2,0 mL</label>
  <button class="quiz-btn" onclick="checkQ1()">Verificar Resposta</button>
  <div id="res1" class="quiz-result"></div>
</div>

<div class="quiz-container">
  <p><strong>2. Na lavagem e enxágue das mãos para a paramentação, qual a posição correta das mãos?</strong></p>
  <label class="quiz-option"><input type="radio" name="q2" value="a"> A) Mãos abaixo dos cotovelos para escorrer para as unhas.</label>
  <label class="quiz-option"><input type="radio" name="q2" value="b"> B) Mãos na mesma altura do quadril.</label>
  <label class="quiz-option"><input type="radio" name="q2" value="c"> C) Mãos mantidas sempre acima do nível dos cotovelos.</label>
  <button class="quiz-btn" onclick="checkQ2()">Verificar Resposta</button>
  <div id="res2" class="quiz-result"></div>
</div>

<div class="quiz-container">
  <p><strong>3. Qual instrumento é utilizado para fixar os panos de campo na pele do paciente?</strong></p>
  <label class="quiz-option"><input type="radio" name="q3" value="a"> A) Pinça Kelly</label>
  <label class="quiz-option"><input type="radio" name="q3" value="b"> B) Pinça de Backhaus</label>
  <label class="quiz-option"><input type="radio" name="q3" value="c"> C) Pinça Halsted Mosquito</label>
  <button class="quiz-btn" onclick="checkQ3()">Verificar Resposta</button>
  <div id="res3" class="quiz-result"></div>
</div>

<script>
  function checkQ1() {
    var q = document.querySelector('input[name="q1"]:checked');
    var res = document.getElementById('res1');
    if (q && q.value === 'b') {
      res.innerHTML = "✅ Correto! (10 kg x 2 mg/kg = 20 mg. 20 mg / 20 mg/mL = 1 mL total).";
      res.style.color = "green";
    } else {
      res.innerHTML = "❌ Incorreto. Lembre-se: Peso x Dose / Concentração!";
      res.style.color = "red";
    }
  }

  function checkQ2() {
    var q = document.querySelector('input[name="q2"]:checked');
    var res = document.getElementById('res2');
    if (q && q.value === 'c') {
      res.innerHTML = "✅ Correto! A água deve sempre escorrer da área mais limpa (mãos) para a menos limpa (cotovelos).";
      res.style.color = "green";
    } else {
      res.innerHTML = "❌ Incorreto. Tente novamente!";
      res.style.color = "red";
    }
  }

  function checkQ3() {
    var q = document.querySelector('input[name="q3"]:checked');
    var res = document.getElementById('res3');
    if (q && q.value === 'b') {
      res.innerHTML = "✅ Correto! A pinça de Backhaus é a pinça de campo oficial.";
      res.style.color = "green";
    } else {
      res.innerHTML = "❌ Incorreto. Kelly e Halsted são pinças hemostáticas!";
      res.style.color = "red";
    }
  }
</script>
