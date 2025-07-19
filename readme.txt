# Instruções de instalação

1. Copie a pasta "autofarm" que está dentro da pasta "java" para o seu gameserver. Na acis, por padrão ela deve ser colocada dentro de "aCis_gameserver/java/net/sf/l2j/gameserver/".
2. Aplique o arquivo patch "acis.diff" que está na pasta "java". Você pode usar o eclipse ou qualquer outro programa que tenha suporte a esse tipo de arquivo. Também é possível fazer as alterações manualmente.
3. Copie a pasta "html/mods" para a pasta onde estão os arquivos htm do seu datapack. 
4. Crie as tabelas no banco de dados usando os arquivos sql da pasta "database".
5. Insira o novo comando no arquivo commandname-e.dat: "201	201	a,autofarm\0"
6. Revise o arquivo de configuração autofarm.properties e altere se for necessário
7. Compile
8. Comece a usar utilizando o comando /autofarm

# Informações importantes

Essas instruções são baseadas na aCis 409. Em versões diferentes ou projetos diferentes, será necessário adaptação.

Você precisa ter o mod IconTable já aplicado no seu projeto. Ele é utilizado para exibir o ícone dos itens do inventário.
https://www.l2jbrasil.com/topic/141832-icontable-para-lxmlreader

Se meu trabalho te ajudou de alguma maneira, considere fazer uma contribuição financeira. Todo o dinheiro recebido será transferido para uma ONG de animais e o comprovante publicado no fórum.

PIX: 60e54@riseup.net
PayPal: ufs@riseup.net
Binance ID: 740297782
