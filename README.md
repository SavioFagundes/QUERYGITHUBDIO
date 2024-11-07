# QUERYGITHUBDIO
COMANDOS DE QUERY DO BOOTCAMP DIO
1-select nome, ano from filmes;
2-select nome, ano from filmes
order by ano;
3-select nome, ano, duracao from filmes
where nome = 'De Volta Para o Futuro';
4-select nome, ano, duracao from filmes
where ano = 1997;
5-select nome, ano, duracao from filmes
where ano > 2000;
6-select nome, ano, duracao from filmes
where Duracao > 100 and Duracao < 150
order by Duracao;
7-select ano as 'Ano', count(id) as Quantidade from filmes
group by ano
order by count(duracao) desc;
8-select id, primeironome, ultimonome, genero from Atores
where genero = 'm';
9-select id, primeironome,ultimonome, genero from atores
where genero = 'F'
order by PrimeiroNome;
10-
