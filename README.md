# GEPGIA - Sistema de Gestão Escolar Inteligente 📚✨

**GEPGIA** (acrônimo para **G**estão **E**scolar em **P**ython com **I**nteligência **A**rtificial) é um sistema de desktop robusto e intuitivo, desenvolvido para simplificar e otimizar a administração de instituições de ensino. Criado com Python e com o auxílio de ferramentas de Inteligência Artificial em seu desenvolvimento, o GEPGIA oferece uma solução completa para gerenciar turmas, matérias, alunos e atividades educacionais.

**Versão Atual:** 1.6.3
**Desenvolvido por:** André Jorge

---

## 🌟 Funcionalidades Principais

O GEPGIA foi projetado para ser uma ferramenta central na gestão escolar, oferecendo:

* **Autenticação Segura:** Tela de Login e Registro para acesso ao sistema.
* **Gerenciamento de Turmas:**
    * Criação e visualização de turmas.
    * Associação de matérias e alunos a turmas específicas.
    * Detalhes e exclusão de turmas.
* **Gerenciamento de Matérias:**
    * Cadastro de novas matérias com nome e descrição.
    * Listagem e exclusão de matérias existentes.
* **Gerenciamento de Alunos:**
    * Convite de alunos para turmas através do e-mail.
    * Listagem de alunos registrados no sistema.
* **Gerenciamento de Atividades Educacionais:**
    * Criação, edição e exclusão de atividades.
    * Visualização de atividades criadas e seus detalhes.
* **Internacionalização:** Suporte a múltiplos idiomas:
    * Português (Brasil)
    * Inglês (English)
    * Espanhol (Español)
    * Alemão (Deutsch)
* **Interface Intuitiva:** Design limpo e fácil de usar para uma ótima experiência do usuário.
* **Informações do Sistema:** Seção "Sobre" com detalhes da versão e do desenvolvedor.

---

## 🖼️ Screenshots

<details>
<summary>Clique para ver as telas do sistema</summary>

**1. Tela de Boas-vindas e Login:**
*Bem-vindo ao Sistema Escolar. Faça login ou registre-se para continuar.*
*(Corresponde a image_253f3c.png)*

**2. Gerenciamento de Turmas:**
*Crie novas turmas, visualize existentes, associe matérias e alunos.*
*(Corresponde a image_253c2e.png)*

**3. Gerenciamento de Matérias:**
*Adicione novas matérias com nome e descrição. Visualize e gerencie as matérias existentes.*
*(Corresponde a image_253c11.png)*

**4. Gerenciamento de Alunos:**
*Convide alunos para turmas e veja a lista de alunos registrados.*
*(Corresponde a image_253bf6.png)*

**5. Gerenciamento de Atividades:**
*Crie, edite e acompanhe as atividades educacionais.*
*(Corresponde a image_253bef.png)*

**6. Configurações de Idioma:**
*Selecione o idioma de preferência para a interface do sistema.*
*(Corresponde a image_253bb3.png)*

**7. Sobre o Sistema Escolar:**
*Informações sobre a versão da aplicação e o desenvolvedor.*
*(Corresponde a image_253f76.png)*

</details>

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem Principal:** Python
* **Interface Gráfica (GUI):** (Especifique aqui a biblioteca GUI utilizada, ex: Tkinter, PyQt, Kivy, CustomTkinter)
* **Banco de Dados:** (Especifique aqui o banco de dados, se houver, ex: SQLite, PostgreSQL)
* **Desenvolvimento Assistido por IA:** Ferramentas de Inteligência Artificial foram utilizadas para auxiliar no processo de desenvolvimento.

---

## 🚀 Como Começar

Para executar o GEPGIA em seu ambiente local, siga os passos abaixo:

**Pré-requisitos:**
* Python 3.x instalado
* pip (gerenciador de pacotes Python)

**Instalação:**

1.  Clone o repositório (ou baixe os arquivos do projeto):
    ```bash
    git clone [https://github.com/seu-usuario/gepgia.git](https://github.com/seu-usuario/gepgia.git) # Substitua pelo link do seu repositório
    cd gepgia
    ```

2.  Crie um ambiente virtual (recomendado):
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3.  Instale as dependências:
    (Crie um arquivo `requirements.txt` com as bibliotecas necessárias e adicione o comando abaixo)
    ```bash
    pip install -r requirements.txt
    ```
    *Exemplo de `requirements.txt` (adapte conforme seu projeto):*
    ```
    # customtkinter  # Exemplo, se você usou CustomTkinter
    # Pillow         # Exemplo, se manipulou imagens para a UI
    # ...outras dependências
    ```

**Executando a Aplicação:**

Execute o arquivo principal da aplicação (geralmente `main.py` ou `app.py`):
```bash
python nome_do_seu_arquivo_principal.py
