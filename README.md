# Atividade RFV com Streamlit

Este projeto faz parte de uma atividade para segmentar clientes usando a metodologia RFV (Recência, Frequência e Valor) e visualizações interativas com Streamlit.

## Descrição

A aplicação segmenta clientes com base em três componentes principais:

- **Recência (R):** Quantidade de dias desde a última compra.
- **Frequência (F):** Quantidade total de compras no período.
- **Valor (V):** Total de dinheiro gasto nas compras no período.

A aplicação também fornece visualizações interativas de histogramas das variáveis RFV.

## Como usar

1. Clone este repositório para o seu computador.

2. Instale as dependências necessárias com o comando:

    ```shell
    pip install -r requirements.txt
    ```

3. Execute a aplicação Streamlit com o comando:

    ```shell
    streamlit run app_RFV_2.py
    ```

4. Faça upload dos dados desejados na aplicação para realizar a segmentação de clientes.

## Resultados

A aplicação gera visualizações interativas e permite o download de resultados em formato Excel.

## Autor

- [Paulo Eduardo](https://github.com/SeuGitHub)

## Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo [LICENSE](LICENSE) para obter mais detalhes.
