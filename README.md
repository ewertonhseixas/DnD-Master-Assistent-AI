# 🧙‍♂️ Assistente do Mestre de D&D (com uma ajudinha de IAs!)

Cansado de passar horas planejando sua próxima sessão de D&D? Seus jogadores sempre fazem o inesperado e te pegam de surpresa? Seus problemas acabaram! Com o **Assistente do Mestre de D&D**, você pode gerar ideias de aventura, encontros balanceados e até planos de contingência com a magia da Inteligência Artificial (e um toque de humor!).

Este projeto utiliza a SDK do Google Gemini e o ADK (Agent Development Kit) para criar um sistema de agentes que trabalham juntos para te ajudar a mestrar. É como ter uma equipe de mini-mestres virtuais no seu cantinho!

## ✨ O que esse assistente faz?

Ele te ajuda a:

*   Criar a **história principal** da sua aventura com base em um tema, número de jogadores e dificuldade.
*   **Balancear os encontros** (combates, enigmas, interações) para que sejam desafiadores na medida certa.
*   Pensar em **soluções alternativas** para quando seus jogadores decidirem ir para a direção completamente oposta à que você planejou (acontece com os melhores!).
*   **Organizar e formatar** toda a informação para que você tenha um guia de mestre prontinho para usar.
*   Incluir **regras de D&D 5E** relevantes para a aventura.

## 🛠️ Tecnologias que fazem a mágica acontecer

*   **Python:** A linguagem de programação por trás de tudo.
*   **Google Gemini API:** O cérebro que gera as ideias.
*   **Google ADK:** Para orquestrar a equipe de agentes.
*   **Bibliotecas Python:** `google-genai`, `google-adk`, `textwrap`, `IPython.display`, `requests`.

## 🚀 Como usar essa belezinha?

1.  **Clone o repositório:**
2.  **Instale as dependências:**
(Se estiver no Colab, pode usar `%pip` diretamente como no código.)
3.  **Configure sua API Key do Google Gemini:**
    *   Vá para o [Google AI Studio](https://aistudio.google.com/preferences/api_key) e crie uma chave de API.
    *   No Google Colab, clique na aba de "Secrets" (chavezinha no painel esquerdo) e adicione sua chave com o nome `GOOGLE_API_KEY`.
4.  **Execute o notebook:** Rode as células do seu notebook Python. O assistente vai te fazer algumas perguntas sobre a aventura que você quer criar.
5.  **Receba sua aventura:** Depois de um tempinho (as IAs precisam pensar!), você terá um rascunho completo da sua one-shot, prontinho para ser adaptado e jogado!

## 📂 Estrutura do Projeto

(Aqui você pode adicionar uma breve descrição das principais partes do seu código, por exemplo: "O código principal está no arquivo `dnd_master_assistant.ipynb` e cada agente é representado por uma função.")

## 🤝 Contribuições

Se você tem ideias para melhorar esse assistente, encontrou um bug (ninguém é perfeito, nem as IAs!) ou quer adicionar novas funcionalidades, suas contribuições são super bem-vindas! Abra uma issue ou envie um pull request.

## 📄 Licença

Este projeto está licenciado sob a Licença [ ]. Veja o arquivo `LICENSE` para mais detalhes.

---

Que suas jogadas de dado sejam sempre altas e suas aventuras inesquecíveis! Divirta-se mestrando!
