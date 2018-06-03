# auxcel

- Sistema de automatizar planilhas em forms

- Objetivo: ler uma planilha e transformar em um sistema

tabela cliente
        idcliente  nome  endereco  telefone
tabela camposAux
        idCampos  iduser  tabelamae   nomeExibicao
tabela valores
        idValor   idCampo   valor
        
        
        
        
tabela tbl_cli
        idcliente = 1 idUser = 11  nome = Jose  endereco = Rua  telefone = 3333
tabela camposAux
        idCampos = 1  iduser = 11  tabelamae = tbl_cli   nomeExibicao = Apelido
        
tabela valores
        idValor = 1   iduser = 11 idCampo = 1   valor = apelido1
        idValor = 2   iduser = 11 idCampo = 1   valor = apelido 2
