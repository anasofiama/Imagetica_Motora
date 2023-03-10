# Imagetica_Motora
Projeto que visa à utilização de sinais de eletroencefalograma (EEG) junto à inteligência artificial para a classificação da imaginação do movimento da mão esquerda ou direita.

A base de dados Graz 2b, como é conhecida, é composta por sinais eletroencefalográficos de 9 voluntários. Cada um deles foi avaliado durante 5 sessões, dentre as quais as duas primeiras aconteceram sem feedback visual, enquanto as três últimas foram realizadas com  feedback na tela. No início de cada sessão foram seguidos alguns passos: 


1) Dois minutos com os olhos abertos, olhando para um ponto fixo; 
2) Um minuto com os olhos fechados; 
3) Um minuto com os olhos se movimentando. O objetivo desses passos é estimar a influência dos sinais de eletrooculografia (EOG) nos sinais de EEG. O eletrooculograma foi gravado utilizando 3 canais. 


Após esses 4 minutos introdutórios, começaram-se as rodadas de Imagética motora. Foram testadas duas classes: imaginação do movimento da mão direita e imaginação do movimento da mão esquerda. Em cada uma das 5 sessões, foram realizadas 6 rodadas. Em cada rodada, porém, foram feitas 20 tentativas (trials) de imagética, sendo 10 referente à classe da mão direita e 10 referente à classe da mão esquerda. Dessa forma, a base disponibiliza 120 tentativas de imagética para cada uma das classes para cada sessão. 


As duas primeiras sessões sem feedback visual consistiram dos seguintes passos: primeiramente o uma cruz de fixação aparecia na tela do voluntário; depois, era feito um estímulo acústico como aviso ou pista, seguido por um estímulo visual com a indicação da classe (direita ou esquerda) por uma seta na tela. Finalmente, o paciente deveria imaginar o movimento indicado pela seta por um período de 4 segundos. 


Em contraste, as três sessões realizadas com feedback seguiram uma sequência diferente. No início de cada rodada, uma carinha neutra de cor cinza aparecia na tela. Então, a pista com a classe era dada no período de 3,5 a 7,5 segundos. Dependendo da pista, o voluntário deveria mover a carinha para a direita ou para a esquerda, de acordo com a pista dada. Durante a imaginação do movimento, a carinha se tornava verde ou vermelha, indicando se o movimento imaginado estava no sentido correto ou errado, respectivamente. 

Foram utilizados 3 eletrodos para a aquisição de EEG (C3, Cz e C4) com uma frequência de amostragem de 250 Hz. Os sinais foram filtrados com filtro passa-banda entre 0,5 Hz e 100 Hz, e um filtro notch de 50 Hz.

Foram usados dessa base de dados ou sinais referentes à aquisição de 3 pacientes, ligados à imaginação de movimento da mão esquerda e da mão direita, no intuito de extrair os principais atributos, avaliar a influência de possíveis fatores externos na frequência do sinal adquirido e posteriormente treinar a classificação das categorias de movimento através de um software com base em inteligência artificial.

