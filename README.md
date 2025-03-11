# Assistente Virtual Financeiro

Este projeto é um assistente virtual financeiro que permite aos usuários gerenciar suas despesas, receitas e orçamentos. O assistente oferece análises de gastos, recomendações personalizadas usando IA generativa, reconhecimento de voz e geração de relatórios em PDF.

## Dependências

O projeto utiliza as seguintes dependências:

- **Flask**: Um microframework para Python que facilita a criação de aplicações web.
- **Flask-Login**: Para gerenciar a autenticação de usuários.
- **Flask-SQLAlchemy**: Para interagir com bancos de dados usando SQLAlchemy.
- **OpenAI**: Para integrar a API da OpenAI e utilizar IA generativa.
- **Matplotlib**: Para gerar gráficos de despesas.
- **Plotly**: Para visualizações interativas.
- **FPDF2**: Para gerar relatórios em PDF.
- **Whisper**: Para reconhecimento de voz.
- **Google Generative AI**: Para análise de gastos com IA.

## Instalação

Para instalar as dependências do projeto, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_DIRETORIO>
   ```

2. Crie um ambiente virtual (opcional, mas recomendado):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## Como Executar o Projeto

Para executar o assistente virtual financeiro, use o seguinte comando:

```bash
python app.py
```

A aplicação estará disponível em `http://127.0.0.1:5000`.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um problema ou enviar um pull request.

## Licença

Este projeto está licenciado sob a MIT License.
