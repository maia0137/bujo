# 📓 Meu Bujo TDAH - Foco & Paz

> Um aplicativo web de arquivo único (Single-File App) desenhado com princípios de Acessibilidade Cognitiva para mentes neurodivergentes.

Bem-vindo ao **Meu Bujo TDAH**! Este projeto nasceu de uma necessidade real: ter um Bullet Journal digital que ajude na organização da vida acadêmica e pessoal, mas **sem causar sobrecarga cognitiva (brain fog)**. 

Aplicativos tradicionais costumam ter menus complexos, notificações infinitas e poluição visual que paralisam a mente de quem tem TDAH. Aqui, a regra é clara: **menos ruído, mais foco.**

## 🧠 Princípios de Acessibilidade Cognitiva Aplicados
* **Compartimentalização:** Apenas uma aba é visível por vez. Você foca nas finanças sem se distrair com as ideias, ou no diário sem olhar o futuro.
* **Fim do Pergaminho Infinito:** O diário é organizado em "sanfonas" por Ano e Mês, evitando a fadiga visual de rolar a tela infinitamente.
* **Âncoras Visuais:** Botões rápidos injetam símbolos (🔴 Urgente, ✅ Concluído, ➡️ Adiado) para que o cérebro categorize o texto rapidamente sem precisar ler tudo.
* **Offline-First e Privado:** Tudo é salvo instantaneamente no `localStorage` do seu navegador. Nenhum dado vai para a nuvem. Sua mente tem a paz de saber que é um espaço 100% seguro.
* **Design Minimalista:** Cores suaves (off-white/sépia) e Dark Mode nativo para conforto ocular.

## 🚀 Funcionalidades

- **📝 Registro Diário:** O coração do app. Agrupado por meses, com botões para checklists, horas e exclusão rápida.
- **🔭 Registro Futuro & Finanças:** Áreas separadas para despejar eventos distantes e controle de parcelas, tirando o peso da memória de trabalho.
- **✅ Habit Tracker Gamificado:** Acompanhe seus hábitos diários com um cálculo automático de ofensiva (Streak 🔥) para garantir aquela dopamina saudável!
- **💡 Ideias & Citações:** Estacionamento mental para novos projetos e frases inspiradoras (formatação automática de citações).
- **🌿 Refúgio (SOS Emocional):** Uma aba fixa de leitura com orientações para momentos de crise, incerteza e dor (Baseado no livro *"Para a vida fazer sentido"* de Herbert Cleber).
- **📥 Importar/Exportar Backup:** Baixe toda a sua vida em um arquivo `.json` com um clique e restaure em qualquer outro dispositivo.

## 🛠️ Como usar (Hospedagem no GitHub Pages)

Este projeto é um **Single-File Web App**. Isso significa que todo o HTML, CSS e JavaScript vivem em perfeita harmonia em um único arquivo.

Para hospedar no seu GitHub Pages (`exemplo.github.io`):

1. Crie um repositório no seu GitHub chamado `EXEMPLO.github.io` (se quiser que seja a página principal) ou `bujo-tdah` (se quiser que seja um sub-site).
2. O arquivo precisa estar nomeado como `index.html`.
3. Faça o upload do `index.html` para a raiz do seu repositório.
4. Vá em **Settings (Configurações) > Pages** e certifique-se de que o GitHub Pages está ativado apontando para a branch `main`.
5. Acesse seu link e comece a usar!
6. Você também tem a opção de usar como arquivo armazenado em seu dispositivo direto em seu navegador de Internet (nesse caso poderá renomear o .html de acordo com a sua preferência).

## 💾 Gestão de Backups

Como o app usa a memória do navegador (`localStorage`), se você limpar o cache ou trocar de celular/PC, os dados não estarão lá. 
**Regra de Ouro:** A cada nova inserção de texto no BuJo (ou semanalmente, se preferir) clique no botão de **Compartilhar (📤)**, baixe o arquivo `meu_bujo_backup.json` e envie para o seu próprio e-mail ou WhatsApp (esta é uma sugestão para armazenar cada backup). Para restaurar, basta abrir o Bujo, clicar no botão **Importar (⬆️)** e selecionar o arquivo.

## 📄 Licença

Este projeto é de código aberto e está licenciado sob a licença **MIT**. 
Sinta-se livre para usar, modificar, estudar e compartilhar. O objetivo é ajudar o maior número possível de pessoas a organizarem suas mentes.

---
*Criado com dedicação e foco na jornada acadêmica e pessoal.*
