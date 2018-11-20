# Imobiliaria-Seu-Lobato

Trabalho Prático de Algoritmos e Técnicas de Programação e Laboratório de Algoritmos e Técnicas de Programação

Seu Lobato é uma imobiliária tradicional na cidade de Trololó - MG e foi inaugurada em 1985, e
tem como objetivo atender bem e fidelizar seus clientes. Atualmente, a imobiliária Seu Lobato
trabalha tanto com locações como vendas de imóveis, no entanto, a procura por imóveis para
locação e aquisição tem aumentado nos últimos anos. Com isso, a concorrência entre as
imobiliárias tem crescido e a agilidade em oferecer serviço de qualidade se torna um diferencial.
Acontece que a Imobiliária Seu Lobato não utiliza sistema, apenas planilhas no excel (algumas
macros) e alguns pequenos sistemas em access, mas nada muito integrado e isso, tem dificultado
bastante na agilidade de respostas para seus clientes. Para resolver seus problemas, a imobiliária
Seu Lobato resolveu solicitar o desenvolvimento de um sistema de gerenciamento imobiliário
para empresa de vocês. Sendo assim, é necessário compreender a real necessidade da imobiliária
e desenvolver um software específico. A seguir foi descrito como deverá ser o sistema, bem
como suas restrições.

O programa cadastra os proprietários dos imóveis, os clientes, os corretores, os imóveis, as
locações, as vendas, além de possuir opções para pesquisas no sistema.

• PROPRIETARIO: código, nome, endereço, telefone

• CLIENTE: código, nome, endereço, telefone, data de nascimento

• CORRETOR: código, nome, telefone, salario

• IMOVEL: código, código proprietário, endereço, categoria (apartamento, casa, cobertura,
lote, etc), tipo (venda ou locação), quantidade de quartos, quantidade de vagas, valor (venda
ou locação), condomínio (valor), status (a vender, a alugar, vendido, com proposta, alugado),
observações (mais detalhes sobre o imóvel)

• LOCACOES: número da locação, código do imóvel, código do cliente/inquilino, valor do
aluguel, taxa administrativa, valor total do proprietário (valor do aluguel menos a taxa
administrativa), data de início da locação, duração da locação

• VENDAS: número da venda, código do imóvel, código do cliente/inquilino, código do
corretor, valor da venda, taxa administrativa, valor total proprietário (valor do venda menos a
taxa administrativa), data da venda

