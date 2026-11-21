# htr-tcc-notebooks

Notebooks do Trabalho de Conclusão de Curso **"Reconhecimento e Análise Semântica de Texto Escrito à mão (HTR) na
língua portuguesa: Estudo Comparativo de Modelos de Inteligência Artificial"** (Engenharia Elétrica, Faculdade de
Tecnologia, Universidade de Brasília, 2026), de Uilmar Vasconcelos da Silva.

Cada notebook gerou números, figuras ou tabelas do texto e está publicado **com as saídas da execução**, de modo
que os resultados podem ser conferidos sem executá-lo.

## Conteúdo

| Notebook | Assunto | Onde aparece no TCC |
|---|---|---|
| NB-01 | Figuras do pré-processamento de imagem | Cap. 2 |
| NB-02 | Comparação de modelos multimodais acessados pela OpenRouter | Cap. 3 |
| NB-03 | Métricas de avaliação (CER, WER, cosseno, BERTScore) | Cap. 2 |
| NB-04 | Treinamento e avaliação do modelo de Puigcerver no BRESSAY | Cap. 4 |
| NB-05 | Protocolo experimental: 14 modelos × 9 condições de pré-processamento | Cap. 5 |
| NB-06 | Era clássica: segmentação, casamento de modelos e características manuais | Cap. 2 (didático) |
| NB-07 | Modelos ocultos de Markov | Cap. 2 (didático) |
| NB-08 | Redes neurais: MLP e CNN | Cap. 2 (didático) |
| NB-09 | Dados sequenciais: RNN, LSTM e GRU | Cap. 2 (didático) |
| NB-10 | CTC e CRNN | Cap. 2 (didático) |
| NB-11 | Atenção, Transformers e modelos de visão e linguagem | Cap. 2 (didático) |
| NB-12 | Correção de redações por modelos de linguagem com a matriz do ENEM | Cap. 5 |

- `notebooks/`: os notebooks executados.
- `saidas/NB-xx/`: figuras, tabelas e arquivos de resultado de cada notebook, com o `manifest.json` da execução
  (data, parâmetros e versões das bibliotecas).

## Execução

Os notebooks utilizam rotinas de pré-processamento, métricas e acesso aos motores de reconhecimento da plataforma
de testes `htr_workbench`, descrita no Capítulo 5 do TCC, cujo código-fonte não é público. Por isso, este
repositório serve para **leitura e conferência** dos resultados; executá-los exige adaptar essas rotinas.
`requirements.txt` lista as bibliotecas utilizadas.

Nas saídas, nomes de máquinas, do projeto de nuvem e caminhos locais foram substituídos por marcadores como
`<vm-gpu>` e `<projeto-gcp>`.

## Dados

Os conjuntos de dados não são redistribuídos aqui:

- **BRESSAY** — redações manuscritas em português brasileiro (Neto et al., ICDAR 2024); obtido junto aos autores.
- **George Washington** — páginas manuscritas com palavras segmentadas (Lavrenko et al., 2004).
- **MNIST** — dígitos manuscritos (LeCun et al., 1998).

## Licença

CC BY 4.0 (ver `LICENSE`). Ao usar este material, cite o TCC.
