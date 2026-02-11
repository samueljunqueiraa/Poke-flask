# Projeto Poke-Flask 🔴⚪

Aplicação Web desenvolvida com **Flask** que integra um modelo de **Machine Learning** para realizar predições relacionadas a Pokémon. O projeto está configurado para deploy em nuvem e utiliza serialização de objetos para a inteligência artificial.

## 🚀 Tecnologias Utilizadas

- **Python** (Linguagem Principal)
- **Flask** (Framework Web)
- **Scikit-Learn** (Machine Learning)
- **Pickle** (Serialização de modelos `.pkl`)
- **Heroku** (Configuração de deploy via `Procfile`)
- **HTML/CSS** (Frontend)

## 📦 Instalação e Execução

Certifique-se de ter o **Python** instalado.

### 1. Instalação das dependências

No terminal, dentro da pasta do projeto, execute:

```bash
pip install -r requirements.txt
```

*(Nota: Se o arquivo requirements.txt não existir, instale as libs manuais: `pip install flask scikit-learn pandas`)*

### 2. Rodando a aplicação

Execute o comando para iniciar o servidor Flask:

```bash
python app.py
```

*Acesse no navegador: http://localhost:5000*

---

### 📂 Estrutura do Projeto

- `app.py`: Arquivo principal da aplicação Web.
- `model.pkl` / `names.pkl`: Arquivos do modelo de IA treinado.
- `modelo.py`: Script utilizado para gerar e treinar o modelo.
- `templates/`: Páginas HTML da interface.
- `static/`: Arquivos estáticos (CSS, Imagens).
- `Procfile`: Arquivo de configuração para deploy no Heroku.

---
Desenvolvido por **[Samuel Junqueira](https://github.com/samueljunqueiraa)**
