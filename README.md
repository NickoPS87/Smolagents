# 🤖 Projeto de Testes com Smol-Agents

Repositório para documentar os estudos e testes com a biblioteca `smol-agents`, focada na criação de agentes de IA para geração de código.


---


## 🚀 Sobre o Projeto

Este projeto é uma exploração prática da biblioteca smolagents da Hugging Face, uma ferramenta poderosa para a criação de agentes de IA autônomos. O objetivo é dissecar e testar seus três componentes principais:

🧠 Agentes: O cérebro da operação (ex: CodeAgent), responsável por planejar e executar tarefas com base em um objetivo.

🔌 Modelos: A fonte de inteligência que alimenta o agente. Este projeto começa utilizando a API da OpenAI (OpenAIModel com GPT-4), mas a biblioteca é flexível e permite a integração com modelos open-source do Hugging Face (InferenceClientModel).

🛠️ Ferramentas: As capacidades práticas do agente. Começamos com o PythonInterpreterTool para geração e execução de código, mas o framework suporta outras ferramentas, como busca na web (WebSearchTool), para expandir as habilidades do agente.

:floppy_disk: O arquivo smolagents.ipynb documenta nosso primeiro caso de uso, gerando um script para 


## :pushpin: Objetivo

:bulb: O objetivo principal deste projeto é explorar as capacidades da biblioteca smolagents da Hugging Face para automatizar tarefas de desenvolvimento. Nosso primeiro caso de uso está implementado no arquivo smolagents.ipynb, que demonstra o fluxo de trabalho gerando um script para monitorar o preço de criptomoedas.

:office: A arquitetura da biblioteca smolagents é flexível, permitindo a conexão com diferentes provedores de modelos de linguagem (LLMs). Para este estudo inicial, utilizamos o OpenAIModel para nos conectarmos à API do GPT-4. No entanto, a biblioteca também está preparada para se conectar a outros modelos, como os disponíveis no Hugging Face, através do InferenceClientModel, bastando para isso instanciar o agente com o objeto de modelo correspondente.


---

## 🛠️ Tecnologias Utilizadas

* **Python 3.12**
* **JupyterLab**
* **Smol-Agents**
* **OpenAI API (GPT-4-turbo)**

---

## ⚙️ Configuração do Ambiente

Para rodar este projeto, siga os passos abaixo. Os comandos são para o terminal **PowerShell** no Windows.

1.  **Clone o repositório:**
    ```powershell
    git clone [https://github.com/NickoPS87/Smolagents.git](https://github.com/NickoPS87/Smolagents.git)
    ```

2.  **Navegue para a pasta do projeto:**
    ```powershell
    cd Smolagents
     ```

3.  **Crie e ative o ambiente virtual:**
    ```powershell
    python -m venv myenv
    .\myenv\Scripts\activate
     ```

4.  **Instale as dependências:**
    O arquivo `requirements.txt` contém todas as bibliotecas necessárias.
    ```powershell
    pip install -r requirements.txt
    ```

5.  **Configure sua Chave de API da OpenAI:**
    Este comando define a chave de API apenas para a sessão atual do terminal.
    ```powershell
    $env:OPENAI_API_KEY = 'sua-chave-secreta-aqui'
    ```

   
---


## ⚡ Como Usar

1.  Com o ambiente virtual ativo e a chave de API configurada, inicie o JupyterLab:
    ```powershell
    jupyter lab
     ```
    
2.  No painel de navegação à esquerda, selecione o arquivo **[Smolagents.ipynb](Smolagents.ipynb)**.


3.  Execute as células do notebook usando `Shift + Enter`.

---



## 👤 Autor

* **Nickolas Santos** → [NickoPS87](https://github.com/NickoPS87)
* ***LinkedIn*** → https://www.linkedin.com/in/nickolas-santos-387bb936/
* ***E-mail para contato*** → djnks87@gmail.com


:rabbit::rabbit::rabbit: EASTER EGG Pesadelo do Sistema :egg::egg::egg:
