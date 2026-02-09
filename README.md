<a name="en"></a>
# 📄 Minimalist LaTeX Resume Template

> [!NOTE]
🇧🇷 **Para a versão em Português**, [clique aqui](#pt)

A clean LaTeX resume template, ATS-friendly and easily adaptable for any professional field. Available in English and Portuguese.

## Features
- **ATS Friendly:** Clean text layer, easily readable by recruitment bots.
- **Structured Code:** Organized in a `src` folder for better maintainability.
- **Clickable Links:** `hyperref` configured for Email, LinkedIn, and GitHub.
- **No Bloat:** Uses standard packages, easy to compile on Overleaf or local LaTeX distributions.

## How to Use

### Option 1: Overleaf (Recommended)
1. Download the file you want from the `src` folder:
   - `src/cv_english.tex` (for English)
   - `src/cv_portuguese.tex` (for Portuguese)
2. Open [Overleaf](https://www.overleaf.com/) and create a **New Project** > **Blank Project**.
3. Paste the code.
4. **Important:** Replace the `[Placeholders]` with your real data aand then remove the brackets.
5. The lists do not use brackets and can be fully customized, allowing you to add or remove items as needed.
6. Click **Recompile**.

### Option 2: Local Compilation
1. Clone this repository:
   ```bash
   git clone [https://github.com/Fe-ctrl/Latex-Resume.git](https://github.com/Fe-ctrl/Latex-Resume.git)
2. Navigate to the folder:
   cd Latex-Resume
3. Compile (example for English):
   pdflatex src/cv_english.tex

<a name="pt"></a>
# 📄 Modelo de Currículo Minimalista em LaTeX

> [!NOTE]
🇺🇸 **For the English version**, [click here](#en)

Um modelo de currículo em LaTeX limpo, amigável para ATS e facilmente adaptável para qualquer área profissional. Disponível em **Inglês** e **Português**.

## Funcionalidades
- **Amigável para ATS:** Camada de texto limpa, facilmente legível por robôs de recrutamento.
- **Código Estruturado:** Organizado em uma pasta `src` para melhor manutenção.
- **Links Clicáveis:** `hyperref` configurado para E-mail, LinkedIn e GitHub.
- **Leve (No Bloat):** Usa pacotes padrão, fácil de compilar no Overleaf ou em distribuições LaTeX locais.

## Como Usar

### Opção 1: Overleaf (Recomendado)
1. Baixe o arquivo desejado da pasta `src`:
   - `src/cv_english.tex` (para Inglês)
   - `src/cv_portuguese.tex` (para Português)
2. Abra o [Overleaf](https://www.overleaf.com/) e crie um **Novo Projeto** > **Projeto em Branco** (Blank Project).
3. Cole o código.
4. **Importante:** Substitua os `[Placeholders]` pelos seus dados reais e depois remova os colchetes.
5. As listas não utilizam colchetes e podem ser totalmente personalizadas, permitindo adicionar ou remover itens conforme necessário.
6. Clique em **Recompile** (Recompilar).

### Opção 2: Compilação Local
1. Clone este repositório:
   ```bash
   git clone [https://github.com/Fe-ctrl/Latex-Resume.git](https://github.com/Fe-ctrl/Latex-Resume.git)
2. Navegue para a pasta:
   cd Latex-Resume
3. Compile (exemplo para Português):
   pdflatex src/cv_portugues.tex
