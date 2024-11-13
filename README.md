# cranieee

Simulação em Java da arquitetura CRAN usando 5G;
O simulador é o Peersim https://peersim.sourceforge.net/

## Passos para execução

- Baixar e realizar unzip do arquivo CodigoGithubCranIEEE2024.zip
- Modificar o arquivo Constantes.java (linha choosenLatSpeed = SPEED.SLOW ou choosenLatSpeed = SPEED.FAST)
- Compilar com Java 1.8+
- Executar `java -cp [path-to-libs] peersim.Simulator [path-to-file]/cran.cfg`
- Os resultados serão mostrados na console.
