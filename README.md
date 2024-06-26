# Machine-Learning-in-Azure-ML
Este é um passo a passo de como ultilizar o Azurte ML para criar um modelo de previsão com pontos de extremidades.

## Criando o Recurso
1. Indo para a sua conta do Azure, você irá clicar em Create a Resource.
![image](https://i.imgur.com/inylpgr.png)
2. Pesquisar por: Azure Machine Learning
![image](https://i.imgur.com/XzIqtrm.png)
3. Clicar neste
![image](https://i.imgur.com/Skgp8bf.png)
4. Clicar em: Create
![image](https://i.imgur.com/p4C2YHd.png)
5. Preencher as seguintes informações e depois clicar em: [Reviw + Create]
![image](https://i.imgur.com/7vhNSN8.png)
6. Clicar em [Create]         
![image](https://i.imgur.com/JABgQUh.png)
7. Aguardar esta etapa por alguns segundos
![image](https://i.imgur.com/Jw04Tl1.png)
8. Clicar em [Go to Resource]       
![image](https://i.imgur.com/MYR7TdG.png)
9. Aqui concluimos a criação e configuração do recurso, clicando em [Launch Studio] abrirá uma outra aba direto no  Estúdio de Aprendizado de Máquina do Azure
![image](https://i.imgur.com/yvL1s0l.png)

# Configurando o Modelo

1. Clicar em [ML Automatizado]
![image](https://i.imgur.com/MVUi5Fc.png)
2. Abrir um novo tarabalho de ML autoamatizado
![image](https://i.imgur.com/A4J1ogx.png)
3. Preencher os seguintes campos e clicar em [Avançar]
![image](https://i.imgur.com/7MYf36Z.png)
4. Aqui vamos selecionar o tipo de dados como [regreção], e logo abaixo clicar em [Criar] para selecionar os dados
![image](https://i.imgur.com/wv8qMty.png)
5. Aqui colocar o nome e a descrição, e colocar o tipo como Tabular
![image](https://i.imgur.com/CWzviJR.png)
6. Afonte de Dados colocar: De Arquivos da Web
![image](https://i.imgur.com/SUwF1PJ.png)
7. Aqui colocar somente a url: https://aka.ms/bike-rentals
![image](https://i.imgur.com/2NcCNCz.png)
8. Nesta confirguração colocar como esta na imagem abaixo, esperar os dados carregarem para clicar em avançar
![image](https://i.imgur.com/CJBV9vl.png)
9. No esquema não muda nada, só clicar em avançar
![image](https://i.imgur.com/QXi243k.png)
10. Não muda nada, clicar em [Criar]
![image](https://i.imgur.com/d9cGvxF.png)
11. Agora selecionar os dados que criamos e clicar em avançar
![image](https://i.imgur.com/6r7vT62.png)
12. Na Coluna de Destino selecionar a opção: Rentals (Integer)
![image](https://i.imgur.com/vc5AOgC.png)
13. Em seguida clicar na engrenagem logo abaixo para abrir as configurçãoes adicionais e preencher como está na imagem abaixo
![image](https://i.imgur.com/LvH9MeG.png)
14. Em Limites preencher assim
![image](https://i.imgur.com/hBPRbzG.png)
15. Em Validar e Testar preencher assim e clicar em avançar
![image](https://i.imgur.com/Pdy4Np7.png)
16. Em Computação deixar assim e avançar
![image](https://i.imgur.com/7YsUWGm.png)
17. Em Examinar, clicar em Enviar Trabalho de Treinamento
![image](https://i.imgur.com/wfoLtdc.png)
18. Aguardar a execução, pode demorar em torno de 10 minutos
![image](https://i.imgur.com/gnLLtd9.png)

# Finalizar
1. Após o Status estiver concluído, no Melhor Resumo de Modelo clicar no link do nome do algoritimo
![image](https://i.imgur.com/Wta93es.png)
2. Clicar em Implantar e escolher Serviço WEB
![image](https://i.imgur.com/SOEzXXW.png)
3. Acrescente esses dados e clique em implantar
![image](https://i.imgur.com/4WRySDS.png)
4. Depois que a execução tiver exito clique no link abaixo de Implantar status
![image](https://i.imgur.com/3n7Q5ww.png)
5. Em testar, coloque as informaçoes do nodigo par ter o resultado.
![image](https://i.imgur.com/cGKgjbg.png)





