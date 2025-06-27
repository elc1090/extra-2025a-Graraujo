# Projeto extra: Gerador de Atas de TCC – Ciência da Computação e Sistemas de Informação

![Screenshot do projeto](https://github.com/user-attachments/assets/54f4c1d8-7b84-4127-82c6-556f2f0891bf)

🔗 **Acesso:** [Gerador de Atas de TCC](https://elc1090.github.io/extra-2025a-Graraujo/)

---

### 👩‍💻 Desenvolvedora

**Giulia Rodrigues de Araújo**  
Graduanda em Ciência da Computação – UFSM

---

### 📝 Produto

Este projeto é uma aplicação web que gera **atas de apresentação de TCC** dos cursos de **Ciência da Computação (CC)** e **Sistemas de Informação (SI)**, da UFSM.

A plataforma permite que os membros da banca preencham os dados da ata de forma prática e organizada, com foco em usabilidade e agilidade no dia da banca.

#### Funcionalidades:
- Formulários web responsivos para preenchimento dos dados da ata
- Assinatura desenhada à mão via **canvas**
- Geração de **PDF** contendo os dados e as assinaturas
- Geração de **link com cabeçalho pré-preenchido** via query string (`?curso=...`)
- Página inicial com escolha do curso (CC ou SI)

---

### ⚙️ Desenvolvimento

A aplicação foi construída com **HTML, CSS e JavaScript puro**, utilizando a biblioteca **Bootstrap 5** para responsividade e estilo. A geração de PDFs foi feita com **jsPDF**, incluindo assinatura capturada em canvas.

Cada curso possui um formulário específico (`atacc.html` e `atasi.html`) e os dados podem ser enviados via URL para facilitar o compartilhamento entre orientador e banca.

Além disso, o sistema valida os campos em tempo real e só permite gerar PDF após todos os campos obrigatórios estarem preenchidos.

---

### 💻 Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- jQuery
- jsPDF
- HTML5 Canvas API

---

### 🛠️ Ambiente de desenvolvimento

- Visual Studio Code
  - Extensões: Live Server, Prettier
- Google Chrome (testes)
- GitHub (repositório e Pages para deploy)

---

### 📚 Referências e créditos

- [jsPDF Documentation](https://github.com/parallax/jsPDF)
- [Bootstrap](https://getbootstrap.com/)
- [Stack Overflow](https://stackoverflow.com/)
- [MDN Web Docs – Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- ChatGPT (OpenAI) – ajuda com estrutura, JS e validações
- Baseado nos modelos de ata utilizados pela UFSM no Centro de Tecnologia

---

Projeto entregue para a disciplina de [Desenvolvimento de Software para a Web](https://github.com/andreainfufsm/elc1090-2025a) – UFSM – 2025a  
Repositório: [extra-2025a-Graraujo](https://github.com/andreainfufsm/extra-2025a-Graraujo)
