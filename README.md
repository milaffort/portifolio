[LEIA-ME.txt](https://github.com/user-attachments/files/35298036/LEIA-ME.txt)
GALERIA CASAMENTO A&R

CONTEÚDO
- index.html  -> a página da galeria
- assets/     -> logo (logo.png), vídeo da capa (fundo.mp4) e imagem de carregamento (capa.jpg)
- fotos/      -> fotos em alta qualidade (usadas ao ampliar e baixar)
- fotos/thumbs/ -> versões menores (usadas na grade, carregam mais rápido)

COMO COLOCAR NO AR (grátis)
1. Acesse app.netlify.com/drop (ou outro serviço de hospedagem).
2. Arraste esta pasta inteira para a página.
3. Você recebe um link. Copie e envie ao cliente.
   Dica: nas configurações do serviço dá para trocar o endereço por um nome seu.

COMO ACRESCENTAR FOTOS
1. Coloque a foto grande em fotos/ (ex.: foto-25.jpg, até ~2000 px de largura).
2. Coloque uma versão menor, com o MESMO nome, em fotos/thumbs/ (~800 px de largura).
3. Abra index.html em um editor de texto e procure a linha que começa com "var P=".
   Acrescente no fim da lista, antes do "]":
   ,{"t":"fotos/thumbs/foto-25.jpg","u":"fotos/foto-25.jpg","s":"Família"}
   O "s" é a aba onde a foto aparece (Noiva, Família ou Mãe e filho).

COMO MUDAR TEXTOS
- Nome e data da capa: procure "Casamento A&amp;R" e "21 de novembro de 2026" no index.html.
- Nomes das abas: procure a linha que começa com "var S=".

IMPORTANTE
- Mantenha as pastas e o index.html juntos, com esses nomes.
- Para ver no computador, basta abrir o index.html no navegador.
