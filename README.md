# 🤖 Projeto de Testes com Smol-Agents

Repositório para documentar os estudos e testes com a biblioteca `smol-agents`, focada na criação de agentes de IA para geração de código.


---


## 🚀 Sobre o Projeto

O objetivo principal deste projeto é explorar as capacidades da biblioteca `smol-agents` da Hugging Face para automatizar tarefas de desenvolvimento. O notebook principal (`smolagents.ipynb`) contém um exemplo prático de como usar um `CodeAgent` para gerar um script Python que monitora o preço de criptomoedas.


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
    
2.  No navegador, abra o notebook **[smolagents.ipynb](smolagents.ipynb)**.


3.  Execute as células do notebook usando `Shift + Enter`.

---



## 👤 Autor

* **Nickolas Santos** → [NickoPS87](https://github.com/NickoPS87)
* ***LinkedIn*** → https://www.linkedin.com/in/nickolas-santos-387bb936/
* ***E-mail para contato*** → djnks87@gmail.com
