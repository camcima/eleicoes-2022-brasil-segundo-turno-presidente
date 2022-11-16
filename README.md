# Eleições 2022 - Brasil - Segundo Turno - Presidente

Dados relativos ao segundo turno das eleições presidenciais brasileiras contendo dados compilados do TSE e IBGE para análise da votação

## boletim_segundo_turno.csv

| Variável | Descrição |
|----------|-----------|
| SG_UF    | Sigla da Unidade da Federação em que ocorreu a eleição. Obs: Urnas no exterior utilizam a sigla ZZ. |
| CD_MUNICIPIO | Código TSE do município onde ocorreu a eleição. Obs: Não confundir com o código do município utilizado pelo IBGE que está numa outra coluna desse arquivo |
| NM_MUNICIPIO | Nome do município onde ocorreu a eleição. |
| NR_ZONA | Número da Zona Eleitoral em que ocorreu a eleição. |
| NR_SECAO | Número da Seção Eleitoral em que ocorreu a eleição. |
| NR_LOCAL_VOTACAO | Número do local de votação referente ao boletim de urna. |
| CD_TIPO_URNA | Código de identificação do tipo de urna. |
| DS_TIPO_URNA | Descrição de identificação do tipo de urna. |
| NR_URNA_EFETIVADA | Número da urna efetivada. |
| QT_APTOS | Quantidade de eleitores aptos a votar naquele município, zona e seção. |
| QT_COMPARECIMENTO | Quantidade de eleitores que compareceram às eleições naquele município, zona e seção. |
| QT_ABSTENCOES | Quantidade de eleitores que não compareceram às eleições naquele município, zona e seção. |
| CD_CARGA_1_URNA_EFETIVADA | Código da Carga 1 da urna efetivada. |
| CD_CARGA_2_URNA_EFETIVADA | Código da Carga 2 da urna efetivada. |
| CD_FLASHCARD_URNA_EFETIVADA | Código do Flashcard de urna efetivada. |
| DT_CARGA_URNA_EFETIVADA | Data da carga da urna efetivada. |
| DT_ABERTURA | Data/hora de abertura da urna eletrônica para votação. |
| DT_ENCERRAMENTO | Data/hora de encerramento da urna eletrônica para votação. |
| QT_ELEITORES_BIOMETRIA_NH | Quantitativo de eleitores com biometria, mas que não foram habilitados por meio dela. |
| DT_EMISSAO_BU | Data/hora de emissão do boletim de urna (BU). |
| QT_VOTOS_LULA | Quantidade de votos no candidato Lula (13) |
| QT_VOTOS_BOLSONARO | Quantidade de votos no candidato Bolsonaro (22) |
| QT_VOTOS_NULO | Quantidade de votos nulos |
| QT_VOTOS_BRANCO | Quantidade de votos brancos |
| DIFF_VOTOS_LULA_BOLSONARO | Diferença de votos do candidato Lula (13) para o candidato Bolsonaro (22) (i.e. QT_VOTOS_LULA - QT_VOTOS_BOLSONARO) |
| DS_MODELO_URNA | Modelo da urna eletrônica utilizada na seção eleitoral |
| PERCENT_VOTOS_LULA | Percentual de votos válidos no candidato Lula (13) |
| PERCENT_VOTOS_BOLSONARO | Percentual de votos válidos no candidato Bolsonaro (22) |
| IS_URNA_NOVA | Campo booleano que indica se a urna é do modelo novo (UE2020) ou não |
| IS_REGIAO_METROPOLITANA | Campo booleano que indica se o município faz parte de uma região metropolitana |
| IS_CAPITAL | Campo booleano que indica se o município é uma capital de estado |
| REGIAO | Região do país onde se encontra a seção (i.e. Norte, Nordeste, Centro-Oeste, Sudeste ou Sul) |
| CD_MUNICIPIO_IBGE | Código do município pelo IBGE |
| LATITUDE | Latitude do município |
| LONGITUDE | Longitude do município |
| POPULACAO | População do município |
| QT_URNAS_NOVAS | Quantidades de urnas novas utilizadas no município |
| QT_URNAS_VELHAS | Quantidade de urnas velhas utilizadas no município (i.e. não-modelo 2020) |
| PERCENT_URNAS_NOVAS | Percentual de urnas novas utilizadas no município |
| PERCENT_URNAS_VELHAS | Percentual de urnas velhas utilizadas no município |
