# TRABALHO DE PI:  Eventando
 Trabalho desenvolvido durante a disciplina de Projeto Integrador do Técnico de Informática para Internet Integrado ao Ensino Médio

## Sumário

### 1. COMPONENTES<br>
Integrantes do grupo:<br>
Esther Moraes Nascimento - esther.ifes2021@gmail.com<br>
Lorena Toraes dos Santos - lorenatoraesdossantos@gmail.com<br>
Sofia Andrade Nascimento - andradesoso17@gmail.com

### 2. MINIMUNDO<br>
> Você consegue organizar seus eventos com facilidade? Você tem dificuldades com o tempo na organização de festividades? E divulgar o evento, é algo fácil? Pensando nisso, desenvolvemos um sistema que ajuda na organização de eventos, sendo possível escolher o tipo de evento que será elaborado, como formatura, reuniões, festas informais, conferências online, entre diversas outras. É possível também, escolher diversos requisitos que são necessários para a elaboração dele, entre eles temos: o local, a atração, a quantidade de convidados, buffet e decoração. Além disso, o sistema possui a opção de enviar os convites gerados para os convidados do evento, contendo o local, data, hora, prazo para confirmação, e se necessário traje e/ou valor do ingresso. Essa aplicação, está disponível nas plataformas web por meio de um site e aplicativo mobile. Ela foi pensada para otimizar a sua organização! Contando com uma interface simples e intuitiva para facilitar a utilização.
 
### 3. PMC<br>
![PMC](https://github.com/esthermoraes/EVENTANDO/blob/main/Desenvolvimento%20do%20sistema/img_PMC.png?raw=true "PMC")

#### 3.1. EAP - ESTRUTURA ANALÍTICA DO PROJETO<br>
a) ![EAP](https://github.com/esthermoraes/EVENTANDO/blob/main/Desenvolvimento%20do%20sistema/img_EAP.png?raw=true "Estrutura Analítica do Projeto")
b.1) ![Dicionário EAP](https://github.com/esthermoraes/EVENTANDO/blob/main/Desenvolvimento%20do%20sistema/img_dicionarioEAP1.png?raw=true "Dicionário EAP 1") 
b.2) ![Dicionário EAP](https://github.com/esthermoraes/EVENTANDO/blob/main/Desenvolvimento%20do%20sistema/img_dicionarioEAP2.png?raw=true "Dicionário EAP 2") 

#### 3.2. REQUISITOS FUNCIONAIS E NÃO FUNCIONAIS<br>
a) ![RF](https://github.com/esthermoraes/EVENTANDO/blob/main/Desenvolvimento%20do%20sistema/img_requisitosFuncionais.png?raw=true "Requisitos Funcionais")
b) ![RNF](https://github.com/esthermoraes/EVENTANDO/blob/main/Desenvolvimento%20do%20sistema/img_requisitosNaoFuncionais.png?raw=true "Requisitos Não Funcionais")

#### 3.3. VALIDAÇÃO DA IDEIA<br>
a) *Link do formulário desenvolvido:* <br> https://forms.gle/N2CqQ6gud3GgbyrM7 <br>
b) *Link para a apresentação dos resultados obtidos:* <br> https://docs.google.com/presentation/d/1XUWC29nwCR0yTu5YozbTAOvrGHfRM9QFxhOgyI0ivOI/edit?usp=sharing

### 4. PERSONAS E HISTÓRIAS DO USUÁRIO<br>
a) *Personas:* <br>
![P1](https://github.com/esthermoraes/Eventando/blob/main/Projeto%20Integrador/persona1.png?raw=true "Persona 1") 
![P2](https://github.com/esthermoraes/Eventando/blob/main/Projeto%20Integrador/persona2.png?raw=true "Persona 2")
![P3](https://github.com/esthermoraes/Eventando/blob/main/Projeto%20Integrador/persona3.png?raw=true "Persona 3") 

b) *Histórias de usuário:* <br>
![HU](https://github.com/esthermoraes/Eventando/blob/main/Projeto%20Integrador/hist_usuario1.png?raw=true "História de usuário 1")
![HU](https://github.com/esthermoraes/Eventando/blob/main/Projeto%20Integrador/hist_usuario2.png?raw=true "História de usuário 2")
![HU](https://github.com/esthermoraes/Eventando/blob/main/Projeto%20Integrador/hist_usuario3.png?raw=true "História de usuário 3")
![HU](https://github.com/esthermoraes/Eventando/blob/main/Projeto%20Integrador/hist_usuario4.png?raw=true "História de usuário 4")
![HU](https://github.com/esthermoraes/Eventando/blob/main/Projeto%20Integrador/hist_usuario5.png?raw=true "História de usuário 5")

### 5. PROTÓTIPOS DO SISTEMA<br>

#### 5.1. PROTÓTIPO DO SISTEMA MOBILE<br>
*Link do protótipo desenvolvido:* <br> https://quant-ux.com/#/apps/64148ae705d723265691b701/design/s12249_12980.html

#### 5.2. PROTÓTIPO DO SISTEMA WEB<br>
*Link do protótipo desenvolvido:* <br> https://quant-ux.com/#/apps/643406af57bd5377df475786/design/s10186_20517.html 

#### 5.3. QUAIS PERGUNTAS PODEM SER RESPONDIDAS COM OS SISTEMA WEB/MOBILE PROPOSTOS?<br>
> O sistema Eventando precisa inicialmente dos seguintes relatórios:
* Relatório que informe os eventos mais favoritados em ordem decrescente: o nome do evento e a quantidade de vezes que foi favoritado.
* Relatório que vai informar a faixa etária do público atingido em ordem decrescente: a idade e a quantidade de vezes que aparece.
* Relatório que informe o formato de evento mais criado: o formato do evento e a quantidade de vezes que aparece.
* Relatório que informe as cores mais utilizadas no convite em ordem decrescente: a cor e a quantidade de vezes que foi utilizada.
* Relatório que vai informar os tipos de contato mais ofertado nos eventos: o tipo de contato e a quantidade de vezes que foi ofertado.
 
 ### 6. MODELO CONCEITUAL<br>
![MC](https://github.com/esthermoraes/Eventando/blob/main/Modelagem%20de%20dados/img_modeloConceitual.png?raw=true "Modelo Conceitual")
      
### 7. DESCRIÇÃO DOS DADOS<br>
    USUARIO: Tabela que armazena as informações relativas ao usuário.
        id_usuario: campo que armazena um código único relativo a cada usuario.
        nome_usuario: campo referente ao nome do usuário.
        data_nasc: campo referente a data de nascimento do usuário.
        senha: campo que armazena a autenticação do email.
        
    EVENTO: Tabela que armazena as informações relativas ao evento.
        id_evento: campo que armazena um código único relativo a cada evento.
        nome_evento: campo referente ao nome do evento.
        objetivo: campo referente ao objetivo do evento.
        data_prevista: campo referente a data prevista do evento.
        privacidade_restrita: campo referente a privacidade do evento.
        atracoes: campo referente as atrações do evento.
        horario: campo referente ao horário do evento.

    TIPO_CONTATO: Tabela que armazena as informações relativas ao tipo contato.
        id_tipo_contato: campo que armazena um código único relativo a cada tipo contato.
        contato: campo que possui o contato de cada tipo contato.
        
    Tem (Tem_tipo_contato_usuario): Tabela que armazena as informações relativas as tabelas tipo contato e usuario.
        descricao: campo que possui a descrição do tipo de contato do usuario.
        
    Possui (Possui_tipo_contato_usuario): Tabela que armazena as informações relativas as tabelas tipo contato e eveno.
        descricao: campo que possui a descrição do tipo de contato do evento.

    EVENTO_PRESENCIAL:Tabela que armazena as informações relativas ao evento presencial.
        buffet: campo que possui o buffet do evento presencial.

    LOCALIZACAO: Tabela que armazena as informações relativas a localização.
        id_localizacao: campo que armazena um código único relativo a cada localização.
        cep: campo que possui o cep de cada localização.
        logradouro: campo que possui o logradouro de cada localização.
        numero: campo que possui o número de cada localização.

    TIPO_LOGRADOURO: Tabela que armazena as informações relativas ao tipo logradouro.
        id_tipo_logradouro: campo que armazena um código único relativo a cada tipo logradouro.
        descricao: campo que possui os tipo de logradouros do tipo logradouro.

    BAIRRO: Tabela que armazena as informações relativas ao bairro.
        id_bairro: campo que armazena um código único relativo a cada bairro.
        descricao: campo que possui os bairros do bairro.

    CIDADE: Tabela que armazena as informações relativas a cidade.
        id_cidade: campo que armazena um código único relativo a cada cidade.
        descricao: campo que possui as cidades da cidade.

    ESTADO: Tabela que armazena as informações relativas ao estado.
        id_estado: campo que armazena um código único relativo a cada estado.
        descricao: campo que possui os estados do estado.

    EVENTO_ONLINE: Tabela que armazena as informações relativas ao evento online.
        plataforma: campo que possui a plataforma do evento online.
        link: campo que possui o link do evento online.

    CONVITE: Tabela que armazena as informações relativas ao convite.
        id_convite: campo que armazena um código único relativo a cada convite.
        cores: campo que possui a cor do convite.
        estilo: campo que possui o estilo do convite.

    LISTA_CONVIDADOS: Tabela que armazena as informações relativas a lista de convidados.
        id_lista_convidados: campo que armazena um código único relativo a cada lista de convidado.
        nome_convidado: campo que armazena o nome do convidado.
        email_convidado: campo que armazena o email do convdado.

### 8.	RASTREABILIDADE DOS ARTEFATOS<br>
a) e b) https://docs.google.com/document/d/1MtG_edmBN31YLc7Xehc2-jbKlWlcu9_z2oYzRO3YA_c/edit?usp=sharing

># MARCO DA ENTREGA 01: DO ITEM 1 AO ITEM 8
<br>

### 9.	MODELO LÓGICO<br>
![ML](https://github.com/esthermoraes/Eventando/blob/main/Modelagem%20de%20dados/img_modeloLogico.png?raw=true "Modelo Lógico")

### 10.	MODELO FÍSICO<br>
        CREATE TABLE USUARIO (
            nome varchar (90),
            data_nasc date,
            senha varchar(50),
            id_usuario serial PRIMARY KEY,
            FK_ESTADO_id_estado int
        );

        CREATE TABLE EVENTO_PRESENCIAL (
            FK_buffet_buffet_PK int,
            FK_EVENTO_id_evento int PRIMARY KEY,
            FK_LOCALIZACAO_id_localizacao int
        );

        CREATE TABLE EVENTO_ONLINE (
            link varchar (500),
            FK_plataforma_plataforma_PK int,
            FK_EVENTO_id_evento int PRIMARY KEY
        );

        CREATE TABLE EVENTO (
            objetivo varchar (255),
            data_prevista date,
            atracoes varchar (300),
            privacidade_restrita BOOL,
            horario time,
            nome varchar(100),
            id_evento serial PRIMARY KEY,
            FK_USUARIO_id_usuario int
        );

        CREATE TABLE CONVITE (
            estilo varchar (20),
            cores varchar (15),
            id_convite serial PRIMARY KEY,
            FK_EVENTO_id_evento int
        );

        CREATE TABLE LISTA_CONVIDADOS (
            nome_convidado varchar (90),
            id_lista_convidados serial PRIMARY KEY,
            email_convidado varchar(150),
            FK_CONVITE_id_convite int
        );

        CREATE TABLE LOCALIZACAO (
            numero int,
            logradouro varchar(250),
            cep varchar(9),
            id_localizacao serial PRIMARY KEY,
            FK_TIPO_LOGRADOURO_id_tipo_logradouro int,
            FK_BAIRRO_id_bairro int
        );

        CREATE TABLE TIPO_LOGRADOURO (
            descricao varchar(50),
            id_tipo_logradouro serial PRIMARY KEY
        );

        CREATE TABLE CIDADE (
            descricao varchar(100),
            id_cidade serial PRIMARY KEY
        );
        CREATE TABLE BAIRRO (
            descricao varchar(100),
            id_bairro serial PRIMARY KEY
        );

        CREATE TABLE ESTADO (
            descricao varchar(2),
            id_estado serial PRIMARY KEY
        );

        CREATE TABLE TIPO_CONTATO (
            id_tipo_contato serial PRIMARY KEY,
            contato varchar(50)
        );

        CREATE TABLE buffet (
            buffet_PK serial NOT NULL PRIMARY KEY,
            buffet varchar (100)
        );

        CREATE TABLE plataforma (
            plataforma_PK serial NOT NULL PRIMARY KEY,
            plataforma varchar(50)
        );

        CREATE TABLE Favorita (
            fk_EVENTO_id_evento int,
            fk_USUARIO_id_usuario int
        );

        CREATE TABLE POSSUI_BAIRRO_CIDADE (
            fk_BAIRRO_id_bairro int,
            fk_CIDADE_id_cidade int
        );

        CREATE TABLE POSSUI_CIDADE_ESTADO (
            fk_CIDADE_id_cidade int,
            fk_ESTADO_id_estado int
        );

        CREATE TABLE POSSUI_TIPO_CONTATO_EVENTO (
            fk_TIPO_CONTATO_id_tipo_contato int,
            fk_EVENTO_id_evento int,
            descricao varchar(150)
        );

        CREATE TABLE TEM_TIPO_CONTATO_USUARIO (
            fk_USUARIO_id_usuario int,
            fk_TIPO_CONTATO_id_tipo_contato int,
            descricao varchar (150)
        );

        ALTER TABLE USUARIO ADD CONSTRAINT FK_USUARIO_2
            FOREIGN KEY (FK_ESTADO_id_estado)
            REFERENCES ESTADO (id_estado)
            ON DELETE RESTRICT;
        
        ALTER TABLE EVENTO_PRESENCIAL ADD CONSTRAINT FK_EVENTO_PRESENCIAL_2
            FOREIGN KEY (FK_buffet_buffet_PK)
            REFERENCES buffet (buffet_PK)
            ON DELETE NO ACTION;
        
        ALTER TABLE EVENTO_PRESENCIAL ADD CONSTRAINT FK_EVENTO_PRESENCIAL_3
            FOREIGN KEY (FK_EVENTO_id_evento)
            REFERENCES EVENTO (id_evento)
            ON DELETE CASCADE;
        
        ALTER TABLE EVENTO_PRESENCIAL ADD CONSTRAINT FK_EVENTO_PRESENCIAL_4
            FOREIGN KEY (FK_LOCALIZACAO_id_localizacao)
            REFERENCES LOCALIZACAO (id_localizacao)
            ON DELETE RESTRICT;
        
        ALTER TABLE EVENTO_ONLINE ADD CONSTRAINT FK_EVENTO_ONLINE_2
            FOREIGN KEY (FK_plataforma_plataforma_PK)
            REFERENCES plataforma (plataforma_PK)
            ON DELETE NO ACTION;
        
        ALTER TABLE EVENTO_ONLINE ADD CONSTRAINT FK_EVENTO_ONLINE_3
            FOREIGN KEY (FK_EVENTO_id_evento)
            REFERENCES EVENTO (id_evento)
            ON DELETE CASCADE;
        
        ALTER TABLE EVENTO ADD CONSTRAINT FK_EVENTO_2
            FOREIGN KEY (FK_USUARIO_id_usuario)
            REFERENCES USUARIO (id_usuario)
            ON DELETE CASCADE;
        
        ALTER TABLE CONVITE ADD CONSTRAINT FK_CONVITE_2
            FOREIGN KEY (FK_EVENTO_id_evento)
            REFERENCES EVENTO (id_evento)
            ON DELETE CASCADE;
        
        ALTER TABLE LISTA_CONVIDADOS ADD CONSTRAINT FK_LISTA_CONVIDADOS_2
            FOREIGN KEY (FK_CONVITE_id_convite)
            REFERENCES CONVITE (id_convite)
            ON DELETE CASCADE;
        
        ALTER TABLE LOCALIZACAO ADD CONSTRAINT FK_LOCALIZACAO_2
            FOREIGN KEY (FK_TIPO_LOGRADOURO_id_tipo_logradouro)
            REFERENCES TIPO_LOGRADOURO (id_tipo_logradouro)
            ON DELETE CASCADE;
        
        ALTER TABLE LOCALIZACAO ADD CONSTRAINT FK_LOCALIZACAO_3
            FOREIGN KEY (FK_BAIRRO_id_bairro)
            REFERENCES BAIRRO (id_bairro)
            ON DELETE CASCADE;
        
        ALTER TABLE Favorita ADD CONSTRAINT FK_Favorita_1
            FOREIGN KEY (fk_EVENTO_id_evento)
            REFERENCES EVENTO (id_evento)
            ON DELETE SET NULL;
        
        ALTER TABLE Favorita ADD CONSTRAINT FK_Favorita_2
            FOREIGN KEY (fk_USUARIO_id_usuario)
            REFERENCES USUARIO (id_usuario)
            ON DELETE SET NULL;
        
        ALTER TABLE Possui_bairro_cidade ADD CONSTRAINT FK_Possui_1
            FOREIGN KEY (fk_BAIRRO_id_bairro)
            REFERENCES BAIRRO (id_bairro)
            ON DELETE RESTRICT;
        
        ALTER TABLE Possui_cidade_estado ADD CONSTRAINT FK_Possui_2
            FOREIGN KEY (fk_CIDADE_id_cidade)
            REFERENCES CIDADE (id_cidade)
            ON DELETE RESTRICT;
        
        /*ALTER TABLE Possui_bairro_cidade ADD CONSTRAINT FK_Possui_3
            FOREIGN KEY (fk_CIDADE_id_cidade)
            REFERENCES CIDADE (id_cidade)
            ON DELETE RESTRICT;*/
        
        ALTER TABLE Possui_cidade_estado ADD CONSTRAINT FK_Possui_5
            FOREIGN KEY (fk_ESTADO_id_estado)
            REFERENCES ESTADO (id_estado)
            ON DELETE RESTRICT;
        
        ALTER TABLE Possui_tipo_contato_evento ADD CONSTRAINT FK_Possui_6
            FOREIGN KEY (fk_TIPO_CONTATO_id_tipo_contato)
            REFERENCES TIPO_CONTATO (id_tipo_contato)
            ON DELETE SET NULL;
        
        ALTER TABLE Possui_tipo_contato_evento ADD CONSTRAINT FK_Possui_4
            FOREIGN KEY (fk_EVENTO_id_evento)
            REFERENCES EVENTO (id_evento)
            ON DELETE SET NULL;
        
        ALTER TABLE Tem_tipo_contato_usuario ADD CONSTRAINT FK_Tem_1
            FOREIGN KEY (fk_USUARIO_id_usuario)
            REFERENCES USUARIO (id_usuario)
            ON DELETE RESTRICT;
        
        ALTER TABLE Tem_tipo_contato_usuario ADD CONSTRAINT FK_Tem_2
            FOREIGN KEY (fk_TIPO_CONTATO_id_tipo_contato)
            REFERENCES TIPO_CONTATO (id_tipo_contato)
            ON DELETE SET NULL;
               
### 11.	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
    a) 
        -- DELETANDO AS TABELAS
        – drop table USUARIO, EVENTO_PRESENCIAL, EVENTO_ONLINE, EVENTO, CONVITE, LISTA_CONVIDADOS, LOCALIZACAO, TIPO_LOGRADOURO, BAIRRO, CIDADE, ESTADO, TIPO_CONTATO, buffet, plataforma, Favorita, Possui_bairro_cidade, Possui_cidade_estado, Possui_tipo_contato_evento, Tem _tipo_contato_usuario

        -- CREATE DAS TABELAS
        CREATE TABLE USUARIO (
            nome varchar (90),
            data_nasc date,
            senha varchar(50),
            id_usuario serial PRIMARY KEY,
            FK_ESTADO_id_estado int
        );

        CREATE TABLE EVENTO_PRESENCIAL (
            FK_buffet_buffet_PK int,
            FK_EVENTO_id_evento int PRIMARY KEY,
            FK_LOCALIZACAO_id_localizacao int
        );

        CREATE TABLE EVENTO_ONLINE (
            link varchar (500),
            FK_plataforma_plataforma_PK int,
            FK_EVENTO_id_evento int PRIMARY KEY
        );

        CREATE TABLE EVENTO (
            objetivo varchar (255),
            data_prevista date,
            atracoes varchar (300),
            privacidade_restrita BOOL,
            horario time,
            nome varchar(100),
            id_evento serial PRIMARY KEY,
            FK_USUARIO_id_usuario int
        );

        CREATE TABLE CONVITE (
            estilo varchar (20),
            cores varchar (15),
            id_convite serial PRIMARY KEY,
            FK_EVENTO_id_evento int
        );

        CREATE TABLE LISTA_CONVIDADOS (
            nome_convidado varchar (90),
            id_lista_convidados serial PRIMARY KEY,
            email_convidado varchar(150),
            FK_CONVITE_id_convite int
        );

        CREATE TABLE LOCALIZACAO (
            numero int,
            logradouro varchar(250),
            cep varchar(9),
            id_localizacao serial PRIMARY KEY,
            FK_TIPO_LOGRADOURO_id_tipo_logradouro int,
            FK_BAIRRO_id_bairro int
        );

        CREATE TABLE TIPO_LOGRADOURO (
            descricao varchar(50),
            id_tipo_logradouro serial PRIMARY KEY
        );

        CREATE TABLE CIDADE (
            descricao varchar(100),
            id_cidade serial PRIMARY KEY
        );
        CREATE TABLE BAIRRO (
            descricao varchar(100),
            id_bairro serial PRIMARY KEY
        );

        CREATE TABLE ESTADO (
            descricao varchar(2),
            id_estado serial PRIMARY KEY
        );

        CREATE TABLE TIPO_CONTATO (
            id_tipo_contato serial PRIMARY KEY,
            contato varchar(50)
        );

        CREATE TABLE buffet (
            buffet_PK serial NOT NULL PRIMARY KEY,
            buffet varchar (100)
        );

        CREATE TABLE plataforma (
            plataforma_PK serial NOT NULL PRIMARY KEY,
            plataforma varchar(50)
        );

        CREATE TABLE Favorita (
            fk_EVENTO_id_evento int,
            fk_USUARIO_id_usuario int
        );

        CREATE TABLE POSSUI_BAIRRO_CIDADE (
            fk_BAIRRO_id_bairro int,
            fk_CIDADE_id_cidade int
        );

        CREATE TABLE POSSUI_CIDADE_ESTADO (
            fk_CIDADE_id_cidade int,
            fk_ESTADO_id_estado int
        );

        CREATE TABLE POSSUI_TIPO_CONTATO_EVENTO (
            fk_TIPO_CONTATO_id_tipo_contato int,
            fk_EVENTO_id_evento int,
            descricao varchar(150)
        );

        CREATE TABLE TEM_TIPO_CONTATO_USUARIO (
            fk_USUARIO_id_usuario int,
            fk_TIPO_CONTATO_id_tipo_contato int,
            descricao varchar (150)
        );

        -- ALTER DAS TABELAS
        ALTER TABLE USUARIO ADD CONSTRAINT FK_USUARIO_2
            FOREIGN KEY (FK_ESTADO_id_estado)
            REFERENCES ESTADO (id_estado)
            ON DELETE RESTRICT;
        
        ALTER TABLE EVENTO_PRESENCIAL ADD CONSTRAINT FK_EVENTO_PRESENCIAL_2
            FOREIGN KEY (FK_buffet_buffet_PK)
            REFERENCES buffet (buffet_PK)
            ON DELETE NO ACTION;
        
        ALTER TABLE EVENTO_PRESENCIAL ADD CONSTRAINT FK_EVENTO_PRESENCIAL_3
            FOREIGN KEY (FK_EVENTO_id_evento)
            REFERENCES EVENTO (id_evento)
            ON DELETE CASCADE;
        
        ALTER TABLE EVENTO_PRESENCIAL ADD CONSTRAINT FK_EVENTO_PRESENCIAL_4
            FOREIGN KEY (FK_LOCALIZACAO_id_localizacao)
            REFERENCES LOCALIZACAO (id_localizacao)
            ON DELETE RESTRICT;
        
        ALTER TABLE EVENTO_ONLINE ADD CONSTRAINT FK_EVENTO_ONLINE_2
            FOREIGN KEY (FK_plataforma_plataforma_PK)
            REFERENCES plataforma (plataforma_PK)
            ON DELETE NO ACTION;
        
        ALTER TABLE EVENTO_ONLINE ADD CONSTRAINT FK_EVENTO_ONLINE_3
            FOREIGN KEY (FK_EVENTO_id_evento)
            REFERENCES EVENTO (id_evento)
            ON DELETE CASCADE;
        
        ALTER TABLE EVENTO ADD CONSTRAINT FK_EVENTO_2
            FOREIGN KEY (FK_USUARIO_id_usuario)
            REFERENCES USUARIO (id_usuario)
            ON DELETE CASCADE;
        
        ALTER TABLE CONVITE ADD CONSTRAINT FK_CONVITE_2
            FOREIGN KEY (FK_EVENTO_id_evento)
            REFERENCES EVENTO (id_evento)
            ON DELETE CASCADE;
        
        ALTER TABLE LISTA_CONVIDADOS ADD CONSTRAINT FK_LISTA_CONVIDADOS_2
            FOREIGN KEY (FK_CONVITE_id_convite)
            REFERENCES CONVITE (id_convite)
            ON DELETE CASCADE;
        
        ALTER TABLE LOCALIZACAO ADD CONSTRAINT FK_LOCALIZACAO_2
            FOREIGN KEY (FK_TIPO_LOGRADOURO_id_tipo_logradouro)
            REFERENCES TIPO_LOGRADOURO (id_tipo_logradouro)
            ON DELETE CASCADE;
        
        ALTER TABLE LOCALIZACAO ADD CONSTRAINT FK_LOCALIZACAO_3
            FOREIGN KEY (FK_BAIRRO_id_bairro)
            REFERENCES BAIRRO (id_bairro)
            ON DELETE CASCADE;
        
        ALTER TABLE Favorita ADD CONSTRAINT FK_Favorita_1
            FOREIGN KEY (fk_EVENTO_id_evento)
            REFERENCES EVENTO (id_evento)
            ON DELETE SET NULL;
        
        ALTER TABLE Favorita ADD CONSTRAINT FK_Favorita_2
            FOREIGN KEY (fk_USUARIO_id_usuario)
            REFERENCES USUARIO (id_usuario)
            ON DELETE SET NULL;
        
        ALTER TABLE Possui_bairro_cidade ADD CONSTRAINT FK_Possui_1
            FOREIGN KEY (fk_BAIRRO_id_bairro)
            REFERENCES BAIRRO (id_bairro)
            ON DELETE RESTRICT;
        
        ALTER TABLE Possui_cidade_estado ADD CONSTRAINT FK_Possui_2
            FOREIGN KEY (fk_CIDADE_id_cidade)
            REFERENCES CIDADE (id_cidade)
            ON DELETE RESTRICT;
        
        /*ALTER TABLE Possui_bairro_cidade ADD CONSTRAINT FK_Possui_3
            FOREIGN KEY (fk_CIDADE_id_cidade)
            REFERENCES CIDADE (id_cidade)
            ON DELETE RESTRICT;*/
        
        ALTER TABLE Possui_cidade_estado ADD CONSTRAINT FK_Possui_5
            FOREIGN KEY (fk_ESTADO_id_estado)
            REFERENCES ESTADO (id_estado)
            ON DELETE RESTRICT;
        
        ALTER TABLE Possui_tipo_contato_evento ADD CONSTRAINT FK_Possui_6
            FOREIGN KEY (fk_TIPO_CONTATO_id_tipo_contato)
            REFERENCES TIPO_CONTATO (id_tipo_contato)
            ON DELETE SET NULL;
        
        ALTER TABLE Possui_tipo_contato_evento ADD CONSTRAINT FK_Possui_4
            FOREIGN KEY (fk_EVENTO_id_evento)
            REFERENCES EVENTO (id_evento)
            ON DELETE SET NULL;
        
        ALTER TABLE Tem_tipo_contato_usuario ADD CONSTRAINT FK_Tem_1
            FOREIGN KEY (fk_USUARIO_id_usuario)
            REFERENCES USUARIO (id_usuario)
            ON DELETE RESTRICT;
        
        ALTER TABLE Tem_tipo_contato_usuario ADD CONSTRAINT FK_Tem_2
            FOREIGN KEY (fk_TIPO_CONTATO_id_tipo_contato)
            REFERENCES TIPO_CONTATO (id_tipo_contato)
            ON DELETE SET NULL;

        -- INSERÇÃO DOS DADOS NAS TABELAS
        INSERT INTO ESTADO (descricao) VALUES
            ('AC'), 
            ('AL'), 
            ('AP'), 
            ('AM'),
            ('BA'), 
            ('CE'),
            ('DF'),
            ('ES'),
            ('GO'),
            ('MA'),
            ('MG'),
            ('MS'),
            ('MG'),
            ('PA'),
            ('PB'),
            ('PN'),
            ('PE'),
            ('PI'),
            ('RJ'),
            ('RN'),
            ('RS'),
            ('RO'),
            ('RR'),
            ('SC'),
            ('SP'),
            ('SE'),
            ('TO');

        INSERT INTO USUARIO (nome, data_nasc, senha, FK_ESTADO_id_estado) VALUES
            ('Tiago Rosa', '1981-11-12', 'tiaguin123', 6),
            ('Maria Souza', '1985-10-20', 'abc123', 2),
            ('Pedro Santos', '1992-07-01', '123456', 3),
            ('Ana Oliveira', '1988-02-12', 'senha456', 4),
            ('Carlos Rodrigues', '1995-09-30', 'abc456', 5),
            ('Juliana Costa', '1993-04-18', 'senha789', 1),
            ('Lucas Almeida', '1991-12-05', '123abc', 3),
            ('Camila Santos', '1987-06-23', 'senha987', 2),
            ('Fernando Lima', '1994-03-11', 'abc789', 4),
            ('Amanda Ferreira', '1996-08-09', '123senha', 5),
            ('Rodrigo Sousa', '1990-11-25', 'senha123', 1),
            ('Isabela Silva', '1985-07-14', 'abc123', 2),
            ('Thiago Costa', '1993-02-01', 'senha456', 3),
            ('Letícia Oliveira', '1989-09-18', 'abc456', 4),
            ('Gustavo Rodrigues', '1995-04-30', 'senha789', 5),
            ('Patrícia Almeida', '1991-11-12', '123abc', 1),
            ('Rafaela Santos', '1988-05-29', 'senha987', 2),
            ('Diego Lima', '1994-01-15', 'abc789', 3),
            ('Renata Ferreira', '1996-06-03', '123senha', 4),
            ('Luiz Sousa', '1990-10-17', 'senha123', 5),
            ('Mariana Silva', '1985-06-06', 'abc123', 1),
            ('Marcelo Costa', '1993-01-24', 'senha456', 2),
            ('Larissa Oliveira', '1989-08-11', 'abc456', 3),
            ('Victor Rodrigues', '1995-03-29', 'senha789', 4),
            ('Carolina Almeida', '1991-10-10', '123abc', 5),
            ('Pedro Santos', '1990-05-15', 'senha123', 1),
            ('Maria Souza', '1985-10-20', 'abc123', 2),
            ('Pedro Santos', '1992-07-01', '123456', 3),
            ('Ana Oliveira', '1988-02-12', 'senha456', 4),
            ('Carlos Rodrigues', '1995-09-30', 'abc456', 5),
            ('Juliana Costa', '1993-04-18', 'senha789', 1),
            ('Lucas Almeida', '1991-12-05', '123abc', 3),
            ('Camila Santos', '1987-06-23', 'senha987', 2),
            ('Fernando Lima', '1994-03-11', 'abc789', 4),
            ('Amanda Ferreira', '1996-08-09', '123senha', 5),
            ('Rodrigo Sousa', '1990-11-25', 'senha123', 1),
            ('Isabela Silva', '1985-07-14', 'abc123', 2),
            ('Thiago Costa', '1993-02-01', 'senha456', 3),
            ('Letícia Oliveira', '1989-09-18', 'abc456', 4),
            ('Gustavo Rodrigues', '1995-04-30', 'senha789', 5),
            ('Patrícia Almeida', '1991-11-12', '123abc', 1),
            ('Rafaela Santos', '1988-05-29', 'senha987', 2),
            ('Diego Lima', '1994-01-15', 'abc789', 3),
            ('Renata Ferreira', '1996-06-03', '123senha', 4),
            ('Luiz Sousa', '1990-10-17', 'senha123', 5),
            ('Mariana Silva', '1985-06-06', 'abc123', 1),
            ('Marcelo Costa', '1993-01-24', 'senha456', 2),
            ('Larissa Oliveira', '1989-08-11', 'abc456', 3),
            ('Victor Rodrigues', '1995-03-29', 'senha789', 4),
            ('Carolina Almeida', '1991-10-10', '123abc', 5);
            /*('João Silva', '1990-05-15', 'senha123', 6), 
                ('Maria Santos', '1985-09-20', 'abcde123', 7), 
                ('Pedro Almeida', '1992-07-10', 'senha456', 8), 
                ('Ana Costa', '1998-01-03', 'abc123', 9), 
                ('Carlos Oliveira', '1987-11-25', 'senha789', 10),
                ('Mariana Pereira', '1995-04-18', '123456', 11), 
                ('Fernando Santos', '1991-08-12', 'senha321', 12), 
                ('Lúcia Rodrigues', '1984-06-27', '654321', 13), 
                ('Rafaela Mendes', '1997-03-08', 'senha987', 14), 
                ('Gabriel Alves', '1993-12-01', 'abcxyz', 15),
                ('Laura Costa', '1990-05-15', 'senha123', 16),
                ('Gabriel Silva', '1985-09-20', 'abcde123', 17),
                ('Carolina Almeida', '1992-07-10', 'senha456', 18),
                ('Lucas Oliveira', '1998-01-03', 'abc123', 19),
                ('Mariana Santos', '1987-11-25', 'senha789', 20),
                ('Rafael Pereira', '1995-04-18', '123456', 21),
                ('Amanda Rodrigues', '1991-08-12', 'senha321', 22),
                ('Bruno Mendes', '1984-06-27', '654321', 23),
                ('Isabela Fernandes', '1997-03-08', 'senha987', 24),
                ('Pedro Alves', '1993-12-01', 'abcxyz', 25),
                ('Sophia Martins', '1994-02-28', 'senha789', 26),
                ('Leonardo Rocha', '1988-10-05', 'abc123', 27);*/
            
        INSERT INTO plataforma (plataforma) VALUES
            ('Google Meet'),
            ('Zoom'),
            ('Microsoft Teams'),
            ('Discord');
        
        INSERT INTO buffet (buffet) VALUES
            ('Buffet A'),
            ('Buffet B'),
            ('Buffet C'),
            ('Buffet D'),
            ('Buffet E'),
            ('Buffet F'),
            ('Buffet G'),
            ('Buffet H'),
            ('Buffet I'),
            ('Buffet J'),
            ('Buffet K'),
            ('Buffet L'),
            ('Buffet M');

        INSERT INTO TIPO_CONTATO (contato) VALUES
            ('E-mail'),
            ('Telefone'),
            ('Facebook'),
            ('Instagram'),
            ('Tik Tok');
                
        INSERT INTO CIDADE (descricao) VALUES 
            ('Rio Branco'),
            ('Maceió'), 
            ('Macapá'),
            ('Manaus'),
            ('Salvador'),
            ('Fortaleza'),
            ('Brasília'), 
            ('Vitória'), 
            ('Goiânia'),
            ('São Luís'),
            ('Cuiabá'), 
            ('Campo Grande'), 
            ('Belo Horizonte'),
            ('Belém'), 
            ('João Pessoa'), 
            ('Curitiba'),
            ('Recife'), 
            ('Teresina'),
            ('Rio de Janeiro'),
            ('Natal'),
            ('Porto Alegre'), 
            ('Porto Velho'), 
            ('Boa Vista'), 
            ('Florianópolis'), 
            ('São Paulo'),
            ('Aracaju'), 
            ('Palmas');

        INSERT INTO BAIRRO (descricao) VALUES
            ('Areial'), 
            ('Estação Experimental'),
            ('Residencial Ouricuri'),
            ('Ponta Verde'),
            ('Pajuçara'), 
            ('Farol'),
            ('Central'), 
            ('Buritizal'), 
            ('Trem'),
            ('Centro'), 
            ('Cidade Nova'), 
            ('Adrianópolis'),
            ('Barra'), 
            ('Itapuã'), 
            ('Rio Vermelho'),
            ('Papicu'), 
            ('Aldeota'), 
            ('Meireles'),
            ('Asa Sul'), 
            ('Asa Norte'), 
            ('Lago Sul'),
            ('Jardim Camburi'), 
            ('Jardim da Penha'), 
            ('Praia do Canto'),
            ('Setor Bueno'), 
            ('Setor Marista'), 
            ('Setor Oeste'),
            ('Calhau'), 
            ('Cohama'), 
            ('Renascença'),
            ('Centro Norte'), 
            ('Araés'), 
            ('Bosque da Saúde'),
            ('Itanhangá'), 
            ('Jardim dos Estados'), 
            ('Tiradentes'),
            ('Savassi'), 
            ('Funcionários'), 
            ('Lourdes'),
            ('Nazaré'), 
            ('Batista Campos'),
            ('Marco'),
            ('Tambaú'),
            ('Manaíra'), 
            ('Bessa'),
            ('Portão'),
            ('Batel'),
            ('Água Verde'),
            ('Boa Viagem'), 
            ('Pina'), 
            ('Casa Forte'),
            ('Garupi'), 
            ('São Cristóvão'), 
            ('Buenos Aires'),
            ('Copacabana'), 
            ('Ipanema'), 
            ('Botafogo'),
            ('Ponta Negra'), 
            ('Lagoa Nova'), 
            ('Cidade Alta'),
            ('Restinga'),
            ('Moinhos de Vento'),
            ('Bela Vista'),
            ('Arigolândia'), 
            ('Caiari'), 
            ('Olaria'),
            ('Mecejana'),
            ('São Francisco'),
            ('Cauamé'),
            ('José Mendes'),
            ('Trindade'), 
            ('Itacorubi'),
            ('Pinheiros'),
            ('Moema'),
            ('Vila Mariana'),
            ('América'), 
            ('Atalaia'),
            ('Grageru'),
            ('Plano Diretor Sul'),
            ('Plano Diretor Norte'), 
            ('Jardim Aureny III');

        INSERT INTO TIPO_LOGRADOURO (descricao) VALUES
            ('Rodovia'),
            ('Avenida'),
            ('Alameda'),
            ('Praça'),
            ('Rua'),
            ('Passarela'),
            ('Vila');

        INSERT INTO EVENTO (objetivo, data_prevista, atracoes, privacidade_restrita, horario, nome, FK_USUARIO_id_usuario) VALUES
            ('Conferência', '2023-06-15', 'Palestrante X, Palestrante Y', TRUE, '09:00', 'Conferência de Tecnologia', 25),
            ('Casamento', '2023-07-20', 'Cerimônia, Banda Z', FALSE, '17:00', 'Casamento de João e Maria' , 2),
            ('Workshop', '2023-08-10', 'Oficina de Fotografia', TRUE, '14:00', 'Workshop de Fotografia',  3),
            ('Festival', '2023-09-05', 'Bandas A, B, C', FALSE, '16:00', 'Festival de Música',  4),
            ('Confraternização', '2023-10-15', 'Amigo Secreto', TRUE, '19:30', 'Confraternização de Fim de Ano', 5),
            ('Palestra', '2023-11-20', 'Palestrante D', FALSE, '15:30', 'Palestra de Empreendedorismo',6),
            ('Feira', '2023-12-10', 'Expositores, Stands', TRUE, '10:00', 'Feira de Negócios', 7),
            ('Encontro', '2023-06-15', 'Networking', FALSE, '17:00', 'Encontro de Profissionais', 8),
            ('Formatura', '2023-07-20', 'Cerimônia, Baile', TRUE, '20:00', 'Formatura da Turma X',  9),
            ('Desfile', '2023-08-10', 'Modelos, Passarela', FALSE, '14:30', 'Desfile de Moda',  10),
            ('Seminário', '2023-09-05', 'Palestrante E, Palestrante F', TRUE, '09:30', 'Seminário de Marketing',  11),
            ('Show', '2023-10-15', 'Artista G', FALSE, '21:00', 'Show ao Vivo',12),
            ('Inauguração', '2023-11-20', 'Cerimônia, Coquetel', TRUE, '18:00', 'Inauguração da Loja',13),
            ('Concerto', '2023-12-10', 'Orquestra H', FALSE, '20:30', 'Concerto Clássico', 14),
            ('Convenção', '2023-06-15', 'Palestrante I, Palestrante J', TRUE, '10:00', 'Convenção Empresarial', 15),
            ('Feijoada', '2023-07-20', 'Samba, Roda de Samba', FALSE, '12:00', 'Feijoada com Samba',16),
            ('Exposição', '2023-08-10', 'Obras de Arte', TRUE, '15:00', 'Exposição de Arte Contemporânea', 17),
            ('Congresso', '2023-09-05', 'Palestrante K, Palestrante L', FALSE, '09:00', 'Congresso de Medicina', 18),
            ('Festa da polenta', '2023-10-15', 'Facilitador M', TRUE, '14:00', 'Festa da polenta', 19),
            ('Semana Cultural', '2023-11-20', 'Diversas Atrações', FALSE, '16:00', 'Semana Cultural da Cidade',20),
            ('Simpósio', '2023-12-10', 'Palestrante N, Palestrante O', TRUE, '09:30', 'Simpósio de Ciência', 21),
            ('Festa do Vinho', '2023-07-20', 'Facilitador Q', TRUE, '14:30', 'Festa do Vinho', 22),
            ('Festa do morango', '2023-07-20', 'Facilitador Q', TRUE, '14:30', 'Festa do morango', 23),
            ('Noivado da Lorena', '2023-08-10', 'Palestrante R', FALSE, '18:00', 'Noivado da Lorena',  24),
            ('Entrega do TCC', '2023-12-13', 'Eventando', TRUE, '21:00', 'Entrega do TCC',  1),
            ('Apresentação de Produto', '2023-06-15', 'Atração A', FALSE, '15:00', 'Evento Presencial 1', 26),
            ('Lançamento de Serviço', '2023-07-20', 'Atração B', TRUE, '18:30', 'Evento Presencial 2', 27),
            ('Conferência de Negócios', '2023-08-10', 'Atração C', FALSE, '11:00', 'Evento Presencial 3', 28),
            ('Workshop de Capacitação', '2023-09-05', 'Atração D', TRUE, '14:30', 'Evento Presencial 4', 29),
            ('Palestra Motivacional', '2023-10-15', 'Atração E', FALSE, '16:00', 'Evento Presencial 5', 30),
            ('Congresso Científico', '2023-11-20', 'Atração F', TRUE, '19:00', 'Evento Presencial 6', 31),
            ('Seminário de Tecnologia', '2023-12-10', 'Atração G', FALSE, '12:30', 'Evento Presencial 7', 32),
            ('Feira de Exposição', '2024-01-15', 'Atração H', TRUE, '15:30', 'Evento Presencial 8', 33),
            ('Encontro de Networking', '2024-02-05', 'Atração I', FALSE, '10:00', 'Evento Presencial 9', 34),
            ('Convenção de Vendas', '2024-03-20', 'Atração J', TRUE, '13:30', 'Evento Presencial 10', 35),
            ('Workshop de Marketing', '2024-04-10', 'Atração K', FALSE, '16:30', 'Evento Presencial 11', 36),
            ('Fórum de Debate', '2024-05-15', 'Atração L', TRUE, '19:30', 'Evento Presencial 12', 37),
            ('Palestra Educativa', '2024-06-05', 'Atração M', FALSE, '11:30', 'Evento Presencial 13', 38),
            ('Conferência de Design', '2024-07-10', 'Atração N', TRUE, '14:30', 'Evento Presencial 14', 39),
            ('Simpósio de Saúde', '2024-08-15', 'Atração O', FALSE, '17:00', 'Evento Presencial 15', 40);

        INSERT INTO EVENTO_ONLINE (link, FK_plataforma_plataforma_PK, FK_EVENTO_id_evento) VALUES
            ('https://meet.com/evento1', 1, 26),
            ('https://zoom.com/evento2', 2, 27),
            ('https://discord.com/evento3', 3, 28),
            ('https://teams.com/evento4', 4, 29),
            ('https://meet.com/evento5', 1, 30),
            ('https://zoom.com/evento6', 2, 31),
            ('https://discord.com/evento7', 3, 32),
            ('https://teams.com/evento8', 4, 33),
            ('https://meet.com/evento9', 1, 34),
            ('https://zoom.com/evento10', 2, 35),
            ('https://discord.com/evento11', 3, 36),
            ('https://teams.com/evento12', 4, 37),
            ('https://meet.com/evento13', 1, 38),
            ('https://zoom.com/evento14', 2, 39),
            ('https://discord.com/evento15', 3, 40);

        INSERT INTO CONVITE (estilo, cores, FK_EVENTO_id_evento) VALUES
            ('Clássico', 'Branco', 1),
            ('Rústico', 'Marrom', 2),
            ('Moderno', 'Preto', 3),
            ('Floral', 'Rosa', 4),
            ('Minimalista', 'Branco', 5),
            ('Elegante', 'Dourado', 6),
            ('Divertido', 'Colorido', 7),
            ('Vintage', 'Bege', 8),
            ('Romântico', 'Vermelho', 9),
            ('Chique', 'Prata', 10),
            ('Abstrato', 'Azul', 11),
            ('Geométrico', 'Amarelo', 12),
            ('Luxuoso', 'Roxo', 13),
            ('Boho', 'Verde', 14),
            ('Clássico', 'Branco', 15),
            ('Rústico', 'Marrom', 16),
            ('Moderno', 'Preto', 17),
            ('Floral', 'Rosa', 18),
            ('Minimalista', 'Branco', 19),
            ('Elegante', 'Dourado', 20),
            ('Divertido', 'Colorido', 21),
            ('Vintage', 'Bege', 22),
            ('Romântico', 'Vermelho', 23),
            ('Chique', 'Prata', 24),
            ('Abstrato', 'Azul', 25),
            ('Geométrico', 'Amarelo', 26),
            ('Luxuoso', 'Roxo', 27),
            ('Boho', 'Verde', 28),
            ('Clássico', 'Branco', 29),
            ('Rústico', 'Marrom', 30),
            ('Moderno', 'Preto', 31),
            ('Floral', 'Rosa', 32),
            ('Minimalista', 'Branco', 33),
            ('Elegante', 'Dourado', 34),
            ('Divertido', 'Colorido', 35),
            ('Vintage', 'Bege', 36),
            ('Romântico', 'Vermelho', 37),
            ('Chique', 'Prata', 38),
            ('Abstrato', 'Azul', 39),
            ('Geométrico', 'Amarelo', 40);

        INSERT INTO LISTA_CONVIDADOS (nome_convidado, email_convidado, FK_CONVITE_id_convite) VALUES
            ('João Silva', 'joao.silva@example.com', 1),
            ('Maria Santos', 'maria.santos@example.com', 1),
            ('Pedro Oliveira', 'pedro.oliveira@example.com', 1),
            ('Ana Pereira', 'ana.pereira@example.com', 1),
            ('Carlos Sousa', 'carlos.sousa@example.com', 1),
            ('Mariana Costa', 'mariana.costa@example.com',2),
            ('Fernando Almeida', 'fernando.almeida@example.com', 2),
            ('Sandra Ferreira', 'sandra.ferreira@example.com', 2),
            ('Ricardo Santos', 'ricardo.santos@example.com', 2),
            ('Isabela Lima', 'isabela.lima@example.com', 2),
            ('Gustavo Gomes', 'gustavo.gomes@example.com', 3),
            ('Laura Oliveira', 'laura.oliveira@example.com', 3),
            ('Rafaella Pereira', 'rafaela.pereira@example.com', 3),
            ('Jorge Sousa', 'jorge.sousa@example.com', 3),
            ('Lívia Costa', 'livia.costa@example.com', 3),
            ('Eduardo Almeida', 'eduardo.almeida@example.com', 4),
            ('Carolina Ferreira', 'carolina.ferreira@example.com', 4),
            ('Antônio Silva', 'antonio.silva@example.com', 4),
            ('Catarina Santos', 'catarina.santos@example.com', 4),
            ('Daniel Oliveira', 'daniel.oliveira@example.com', 4),
            ('Vitória Pereira', 'vitoria.pereira@example.com', 5),
            ('Rui Sousa', 'rui.sousa@example.com',5),
            ('Lara Costa', 'lara.costa@example.com', 5),
            ('Henrique Almeida', 'henrique.almeida@example.com', 5),
            ('Tatiana Ferreira', 'tatiana.ferreira@example.com', 5),
            ('Luís Santos', 'luis.santos@example.com', 6),
            ('Mariana Lima', 'mariana.lima@example.com', 6),
            ('Hugo Gomes', 'hugo.gomes@example.com', 6),
            ('Beatriz Oliveira', 'beatriz.oliveira@example.com', 6),
            ('Gabriel Pereira', 'gabriel.pereira@example.com', 6),
            ('Isabella Sousa', 'isabella.sousa@example.com', 7),
            ('Ricardo Costa', 'ricardo.costa@example.com', 7),
            ('Amanda Almeida', 'amanda.almeida@example.com', 7),
            ('Felipe Ferreira', 'felipe.ferreira@example.com', 7),
            ('Manuela Silva', 'manuela.silva@example.com', 7),
            ('Henrique Santos', 'henrique.santos@example.com', 8),
            ('Marina Oliveira', 'marina.oliveira@example.com', 8),
            ('Leonardo Pereira', 'leonardo.pereira@example.com', 8),
            ('Ryan Martin', 'ryanmartins@example.com', 8),
            ('Lyon Mendes', 'lyonmendes@example.com', 8),
            ('Lucas Santos', 'lucas.santos@example.com', 9),
            ('Fernanda Silva', 'fernanda.silva@example.com',9),
            ('Rafael Oliveira', 'rafael.oliveira@example.com', 9),
            ('Juliana Pereira', 'juliana.pereira@example.com',9),
            ('Marcelo Sousa', 'marcelo.sousa@example.com', 9),
            ('Camila Costa', 'camila.costa@example.com', 10),
            ('Gustavo Almeida', 'gustavo.almeida@example.com', 10),
            ('Carolina Ferreira', 'carolina.ferreira@example.com', 10),
            ('Ricardo Santos', 'ricardo.santos@example.com', 10),
            ('Emily Johnson', 'emily.johnson@example.com', 10),
            ('Arthur Sampaio', 'arthursampaio@example.com', 11),
            ('Olivia Almeida', 'oliviaalmeida@example.com', 11),
            ('Peter Soon', 'petersoon@example.com', 11),
            ('Alice Vieira', 'alicevieira@example.com', 11),
            ('Miguel Torres', 'migueltorres@example.com', 11),
            ('Laura Albuquerque', 'laurabuq@example.com',12),
            ('Flávio Assunção', 'flavioassuncao@example.com', 12),
            ('Debora Seco', 'deboraseco@example.com', 12),
            ('Cauã Reymond', 'cauarey@example.com', 12),
            ('Vitória Estrada', 'vitoriaestrada@example.com', 12),
            ('Bruna Marquenize', 'brumarq@example.com', 13),
            ('Tatá Werneck', 'tatawerneck@example.com', 13),
            ('Marina Ruy Barbosa', 'marirbarb@example.com', 13),
            ('Jorge Blanco', 'jorge.blanco@example.com', 13),
            ('Rafael Vitti', 'rafa.vitti@example.com', 13),
            ('Emanuelle Araújo', 'emaraujo@example.com', 14),
            ('Carolina Herrera', 'carolina.herrera@example.com', 14),
            ('Angélica Silva', 'angel.silva@example.com', 14),
            ('Catarina Pyerce', 'catarina.pyerce@example.com', 14),
            ('Daniel Trindade', 'daniel.trindade@example.com', 14),
            ('Vanuza Lima', 'vanuzalima@example.com', 15),
            ('Rui Barbosa', 'ruibarb@example.com', 15),
            ('Rhuan Silveira' , 'rhuansilv@example.com', 15),
            ('Henri Brandt', 'henri.brandt@example.com', 15),
            ('Tati Quebra Barraco', 'tati.qb@example.com', 15),
            ('Luiz Inácio', 'lula13@example.com', 16),
            ('Bruno Unzueta', 'bruzueta@example.com',16),
            ('Hugo Boss', 'hugo.boss@example.com', 16),
            ('Beatriz Trancoso', 'beatriz.oliveira@example.com', 16),
            ('Gabriel Reis', 'gabrielreis@example.com', 16),
            ('Isís Valverde', 'isisvalverde@example.com', 17),
            ('Ricardo Tozzi', 'ricardotozzi@example.com', 17),
            ('Felipe Titto', 'felipetitto@example.com', 17),
            ('Felipe Frechiani', 'felipe.frechiani@example.com', 17),
            ('Manuela Larissa', 'manuela.larissa@example.com', 17),
            ('Davi Brandt', 'davibrandt@example.com', 18),
            ('Paolla Oliveira', 'paollaoliveira@example.com', 18),
            ('Leonardo Avilla', 'leonardo.avilla@example.com', 18),
            ('Ryan Menezes', 'ryanm@example.com', 18),
            ('Harry Styles', 'harry@example.com',18),
            ('Bruno Mars', 'bmars@example.com', 19),
            ('Fernanda Paes Leme', 'fernanda.pl@example.com',19),
            ('Nial Horan', 'nialh@example.com', 19),
            ('Juliana Paiva', 'juliana.paiv@example.com',19),
            ('Nicolas Prattes', 'nicprattes@example.com', 19),
            ('Camila Pitanga', 'camilaptga@example.com', 20),
            ('Gustavo Tubarao', 'gustavotu@example.com', 20),
            ('Carol Ferraz', 'carolina.ferr@example.com', 20),
            ('Santiago Mendes', 'santmen@example.com', 20),
            ('Emily Garcia', 'emily.garcia@example.com', 20),
            ('João Gomes', 'joao.gomes@example.com', 21),
            ('Maria da Graça', 'maria.graça@example.com', 21),
            ('Shawn Mendes', 'bolinho@example.com', 21),
            ('Ana Castella', 'anacastella@example.com', 21),
            ('Fabiola Nascimento', 'fabiolan@example.com', 21),
            ('Otaviano Costa', 'otacosta@example.com', 22),
            ('Virginia Fonseca', 'virginiafonseca@example.com', 22),
            ('Ana Mosconi', 'anamosc@example.com', 22),
            ('Vicente Vieira', 'vivieira@example.com', 22),
            ('Raquel Davilla', 'raquelDavilla@example.com', 22),
            ('Guilherme Pessoa', 'guilhermep@example.com', 23),
            ('Mirella Santos', 'Mirellasant@example.com', 23),
            ('Romulo Estrela', 'romuloestrela@example.com', 23),
            ('Grazzi Massafera', 'grazzima@example.com', 23),
            ('Josh Beauchamp', 'joshbeau@example.com', 23),
            ('Sabina Hidalgo', 'hidalgosab@example.com', 24),
            ('Maisa Silva', 'maisasil@example.com', 24),
            ('Melissa Maia', 'melissamel@example.com', 24),
            ('Karoline Lima', 'karlima@example.com', 24),
            ('Giovanna Grigio', 'giiogrigio@example.com', 24),
            ('Raissa Chadad', 'raissachadad@example.com', 25),
            ('Gabriela Saraivah', 'gabrielasaraivah@example.com', 25),
            ('Guilherme Oliveira', 'guioli@example.com', 25),
            ('Gabriel Santana', 'gabsant@example.com', 25),
            ('Livia Inhudes', 'liviainhu@example.com', 25),
            ('Cintia Cruz', 'cintiacruz@example.com', 26),
            ('Julia Oliver', 'jujuoli@example.com', 26),
            ('Julia Gomes', 'jugomes@example.com', 26),
            ('Sophia Valverde', 'sosoval@example.com', 26),
            ('Mateus Lustosa', 'mateuslustosa@example.com', 26),
            ('Isabella Paolli', 'isabellapaolli@example.com', 27),
            ('Luiza Parente', 'Luizap@example.com', 27),
            ('Virgina Wanderlei', 'virginiaderlei@example.com', 27),
            ('Ananda Morais', 'anandamorais@example.com', 27),
            ('Julia Franco', 'jufrancoo@example.com', 27),
            ('Isabela Fernandes', 'isabelfernandes@example.com', 28),
            ('João Pedro Mota', 'jpmot@example.com', 28),
            ('Gustavo Paz', 'gustavopazz@example.com', 28),
            ('Lucas Burgatti', 'lucasburg@example.com', 28),
            ('Igor Jansen', 'igorjansen@example.com', 28),
            ('Duda Pimenta', 'dudapiment@example.com', 29),
            ('Luisa Besser', 'lbresser@example.com', 29),
            ('Felipe Fontelles', 'felipefont@example.com', 29),
            ('Eric Ferreira', 'ericferr@example.com', 29),
            ('André Luis Sousa', 'andrelsou@example.com', 29),
            ('João Vitor Dourado', 'jvdourado@example.com', 30),
            ('Isadora Amaro', 'isadoraamar@example.com', 30),
            ('Valentina Costa', 'valencost@example.com', 30),
            ('Julia Holanda', 'juliaH@example.com', 30),
            ('Esther Marcos', 'esthermar@example.com', 30),
            ('Pedro Scooby', 'pedroscoo@example.com', 31),
            ('Carla Diaz', 'carladiaz@example.com', 31),
            ('Arthur Aguiar', 'arthuag@example.com', 31),
            ('Lua Blanco', 'luablanco@example.com', 31),
            ('Chay Suede', 'chaysuede@example.com', 31),
            ('Sheron Menezes', 'sheronmen@example.com', 32),
            ('Sophia Abrahão', 'sophiabrah@example.com', 32),
            ('Mel Fronckowiak', 'melfron@example.com', 32),
            ('Duda Reis', 'dudarei@example.com', 32),
            ('Lisa Barcellos', 'lisabar@example.com', 32),
            ('Jordana Maia', 'jordanamaia@example.com', 33),
            ('Taina Costa', 'tainacost@example.com', 33),
            ('Lara Silva', 'larasilv@example.com', 33),
            ('Tata Estaniecki', 'tataestaniecki@example.com', 33),
            ('Julio Cocielo', 'juliococielo@example.com', 33),
            ('Duda Kropf', 'dudakropf@example.com', 34),
            ('Fernanda Concon', 'fercon@example.com', 34),
            ('Ester Exposito', 'esteexposit@example.com', 34),
            ('Giovanna Bichels', 'giovannab@example.com', 34),
            ('Nina Baiocchi', 'ninabaio@example.com', 34),
            ('Júlia Rissato', 'jujur@example.com', 35),
            ('Giovanni Robatini', 'giovannir@example.com', 35),
            ('Igor Casseb', 'igorcas@example.com', 35),
            ('Cecilia Pedersoli', 'ceciped@example.com', 35),
            ('Malu Borges', 'maluborg@example.com', 35),
            ('Vanessa Lopes', 'vanlop@example.com', 36),
            ('Lucas Abreu', 'lucasA@example.com', 36),
            ('Clara Garcia', 'claragarcia@example.com', 36),
            ('Lucas Maciel', 'lucasmaciel@example.com', 36),
            ('Juliano Floss', 'julianoloss@example.com', 36),
            ('Julia Mazzocco', 'julimazz@example.com', 37),
            ('Ana Mazzocco', 'anamazz@example.com', 37),
            ('Malu Camargo', 'malumargo@example.com', 37),
            ('Priscila Caliari', 'pricalliari@example.com', 37),
            ('Jessi Shein', 'jessishein@example.com', 37),
            ('Nicholas Coutinho', 'nichcout@example.com', 38),
            ('Allan Jeong', 'allanjeong@example.com', 38),
            ('Thalita Meneghim', 'thalitamen@example.com', 38),
            ('Mariana Menezes', 'marianamen@example.com', 38),
            ('Arthur Bicalho', 'arthurbicalhoo@example.com', 38),
            ('Mharessa Fernanda', 'mhafern@example.com', 39),
            ('Bernardo Busnello', 'bernbusnello@example.com', 39),
            ('Caio Castro', 'caiocast@example.com', 39),
            ('Crystal Braz', 'crybrazz@example.com', 39),
            ('Duda Stecchini', 'dudatech@example.com', 39),
            ('Jully Molinna', 'jullymon@example.com', 40),
            ('Aurora Sucinta', 'ausucinta@example.com', 40),
            ('Giovanna Chaves', 'giochav@example.com', 40),
            ('Felipe Neto', 'feneto@example.com', 40),
            ('Bruna Correa', 'brureaa@example.com', 40);

        INSERT INTO LOCALIZACAO (numero, logradouro, cep, FK_TIPO_LOGRADOURO_id_tipo_logradouro, FK_BAIRRO_id_bairro) VALUES
            (1, ' A', '12345-678', 1, 1),
            (2, ' B', '98765-432', 5, 4),
            (3, ' C', '54321-876', 3, 7),
            (4, ' D', '11111-111', 6, 10),
            (5, ' E', '22222-222', 2, 13),
            (6, ' F', '33333-333', 3, 16),
            (7, 'G', '44444-444', 1, 19),
            (8, ' H', '55555-555', 2, 22),
            (9, 'I', '66666-666', 3, 25),
            (10, ' J', '77777-777', 5, 28),
            (11, ' K', '88888-888', 2, 31),
            (12, ' L', '99999-999', 3, 34),
            (13, 'M', '00000-000', 1, 37),
            (14, ' N', '11111-111', 2, 40),
            (15, 'O', '22222-222', 6, 43),
            (16, 'P', '33333-333', 1, 46),
            (17, ' Q', '44444-444', 4, 49),
            (18, ' R', '55555-555', 7, 52),
            (19, ' S', '66666-666', 1, 55),
            (20, 'T', '77777-777', 2, 58),
            (21, ' U', '88888-888', 4, 61),
            (22, 'V', '99999-999', 1, 64),
            (23, ' W', '10101-101', 6, 67),
            (24, ' X', '12121-121', 3, 70),
            (25, 'Y', '13131-131', 7, 73);
            
        INSERT INTO Favorita (fk_EVENTO_id_evento, fk_USUARIO_id_usuario) VALUES
            (1, 1),
            (1, 2),
            (1, 3),
            (1, 4),
            (1, 5),
            (3, 6),
            (2, 7),
            (25, 8),
            (13, 9),
            (20, 10),
            (30, 11),
            (35, 12),
            (22, 13),
            (25, 14),
            (25, 15),
            (25, 16),
            (25, 17),
            (25, 18),
            (28, 19),
            (28, 20),
            (28, 21),
            (13, 22),
            (30, 23),
            (25, 24),
            (25, 25),
            (24, 26),
            (24, 27),
            (24, 28),
            (24, 29),
            (24, 30),
            (1, 31),
            (5, 32),
            (7, 34),
            (10, 35),
            (15, 36),
            (12, 37),
            (23, 38),
            (25, 39),
            (24, 40),
            (24, 41),
            (24, 42),
            (24, 43),
            (24, 44),
            (28, 45),
            (10, 45),
            (25, 46),
            (37, 47),
            (17, 48),
            (22, 49),
            (13, 50);

        INSERT INTO EVENTO_PRESENCIAL (FK_buffet_buffet_PK, FK_EVENTO_id_evento, FK_LOCALIZACAO_id_localizacao) VALUES 
            (1, 1, 1),
            (1, 2, 2),
            (2, 3, 3),
            (2, 4, 4),
            (3, 5, 5),
            (3, 6, 6),
            (4, 7, 7),
            (4, 8, 8),
            (5, 9, 9),
            (5, 10, 10),
            (6, 11, 11),
            (6, 12, 12),
            (7, 13, 13),
            (7, 14, 14),
            (8, 15, 15),
            (8, 16, 16),
            (9, 17, 17),
            (9, 18, 18),
            (10, 19, 19),
            (10, 20, 20),
            (11, 21, 21),
            (11, 22, 22),
            (12, 23, 23),
            (12, 24, 24),
            (13, 25, 25);

        INSERT INTO Possui_bairro_cidade (FK_BAIRRO_id_bairro, FK_CIDADE_id_cidade) VALUES
            (1, 1),
            (4, 2),
            (7, 3),
            (10, 4),
            (13,5),
            (16, 6),
            (19, 7),
            (22, 8),
            (25, 9),
            (28,10),
            (1, 11),
            (4, 12),
            (7, 13),
            (10, 14),
            (13,15),
            (16, 16),
            (19, 17),
            (22, 18),
            (25, 19),
            (28,20),
            (31, 21),
            (34, 22),
            (37, 23),
            (40, 24),
            (43, 25);

        INSERT INTO Possui_cidade_estado (FK_CIDADE_id_cidade, FK_ESTADO_id_estado) VALUES
            (1, 1),
            (2, 2),
            (3, 3),
            (4, 4),
            (5, 5),
            (6, 6),
            (7, 7),
            (8,8),
            (9, 9),
            (10, 10),
            (11, 11),
            (12, 12),
            (13, 13),
            (14, 14),
            (15, 15),
            (16, 16),
            (17, 17),
            (18, 18),
            (19, 19),
            (20, 20),
            (21, 21),
            (22, 22),
            (23, 23),
            (24, 24),
            (25, 25),
            (26, 26),
            (27, 27);

        INSERT INTO Possui_tipo_contato_evento  (descricao, FK_TIPO_CONTATO_id_tipo_contato, FK_EVENTO_id_evento) VALUES
            ('tecconferencia' ,3, 1),
            ('jemnoivos' ,3, 2),
            ('fotoshop' , 3, 3),
            ('musicfest' ,3, 4),
            ('(27)99223-9636', 2, 5),
            ('(21)99265-5593', 2, 6),
            ('(11)99205-9693', 2, 7),
            ('(84)98525-9493', 2, 8),
            ('(21)99385-9293', 2, 9),
            ('(11)99265-9773', 2, 10),
            ('marketingsem@gmail.com',1, 11),
            ('showaovivo@gmail.com',1, 12),
            ('lojdalore@gmail.com',1, 13),
            ('classiconsert@gmail.com',1, 14),
            ('sambacomfeijao@gmail.com',1, 15),
            ('expoarte@gmail.com',1, 16),
            ('@medcongre' ,4 ,17),
            ('@polentafest',4 ,18),
            ('@citycultura' ,4 ,19),
            ('@cienciasimple' ,4 ,20),
            ('@vinhofest' ,4 ,21),
            ('@morangofest' ,4 ,22),
            ('@lewedding' ,4 ,23),
            ('@eventando.nozes' ,4 ,24),
            ('@eventpresent1' ,4 ,25),
            ('@eventpresent2' ,4 ,26),
            ('@eventpresent3' ,4 ,27),
            ('@eventpresent4' ,4 ,28),
            ('@eventpresent5' ,4 ,29),
            ('@eventpresent6' ,4 ,30),
            ('@eventpresent7' ,4 ,31),
            ('@eventpresent8' ,4 ,32),
            ('@eventpresent9' ,5, 33),
            ('@eventpresent10' ,5, 34),
            ('@eventpresent11' ,5, 35),
            ('@eventpresent12' ,5, 36),
            ('@eventpresent13' ,5, 37),
            ('@eventpresent14' ,5, 38),
            ('@eventpresent15' ,5, 39),
            ('@eventpresent16' ,5, 40);

        INSERT INTO TEM_TIPO_CONTATO_USUARIO (FK_TIPO_CONTATO_id_tipo_contato, descricao, FK_USUARIO_id_usuario) VALUES
            (1,'tiagorosa@gmail.com',1),
            (2,'(85)99812-4767', 1),
            (1,'mariasouza@gmail.com',2),
            (2,'(82)99812-4765', 2),
            (1,'pedrosantos@gmail.com',3),
            (2,'(82)99712-4768', 3),
            (1,'anaoliveira@gmail.com',4),
            (2,'(92)99212-4767', 4),
            (1,'carlosrodrigues@gmail.com',5),
            (2,'(71)99312-4767', 5),
            (1,'julianacosta@gmail.com',6),
            (2,'(68)99812-8888', 6),
            (1,'lucasalmeida@gmail.com',7),
            (2,'(82)99812-2425',7),
            (1,'camilasantos@gmail.com',8),
            (2,'(96)99813-4767', 8),
            (1,'fernandolima@gmail.com',9),
            (2,'(92)99502-4767', 9),
            (1,'amandaferreira@gmail.com',10),
            (2,'(71)99912-4767', 10),
            (1,'rodrigosousa@gmail.com',11),
            (2,'(68)99112-4767', 11),
            (1,'isabelasilva@gmail.com',12),
            (2,'(82)99812-4467', 12),
            (1,'tiagocosta@gmail.com',13),
            (2,'(96)99812-4755', 13),
            (1,'leticiaoliveira@gmail.com',14),
            (2,'(92)9950-4616', 14),
            (1,'gustavorodrigues@gmail.com',15),
            (2,'(71)99504-6166', 15),
            (1,'patriciaalmeida@gmail.com',16),
            (2,'(68)98181-5344', 16),
            (1,'rafaelasantos@gmail.com',17),
            (2,'(82)98157-4947', 17),
            (1,'diegolima@gmail.com',18),
            (2,'(96)99657-0589', 18),
            (1,'renataferreira@gmail.com',19),
            (2,'(92)98895-5725', 19),
            (1,'luizsouza@gmail.com',20),
            (2,'(71)99500-0028', 20),
            (1,'marianasilva@gmail.com',21),
            (2,'(68)99744-5347', 21),
            (1,'marcelocosta@gmail.com',22),
            (2,'(82)99662-3266', 22),
            (1,'larissaoliveira@gmail.com',23),
            (2,'(96)98838-8919', 23),
            (1,'victorodrigues@gmail.com',24),
            (2,'(92)99205-1225', 24),
            (1,'carolinalmeida@gmail.com',25),
            (2,'(71)99737-6136', 25),
            (1,'pedroosantos@gmail.com',26),
            (2,'(68)99895-0028',26),
            (1,'marisouza@gmail.com',27),
            (2,'(82)998867-2845', 27),
            (1,'pedrinhosant@gmail.com',28),
            (2,'(96)99981-7077', 28),
            (1,'anaaoliv@gmail.com',29),
            (2,'(92)99651-7829', 29),
            (1,'carlinr@gmail.com',30),
            (2,'(71)99867-7339', 30),
            (1,'jucost@gmail.com',31),
            (2,'(68)99291-0382',31),
            (1,'lumeida@gmail.com',32),
            (2,'(82)99527-3201', 32),
            (1,'camsantos@gmail.com',33),
            (2,'(96)99829-6191', 33),
            (1,'felima@gmail.com',34),
            (2,'(92)98142-5937', 34),
            (1,'mandsferr@gmail.com',35),
            (2,'(71)99610-7736', 35),
            (1,'rosousa@gmail.com',36),
            (2,'(68)99761-1853', 36),
            (1,'isasilv@gmail.com',37),
            (2,'(82)99752-5329', 37),
            (1,'thicosta@gmail.com',38),
            (2,'(96)98857-9546', 38),
            (1,'letsoliva@gmail.com',39),
            (2,'(92)998823-1756', 39),
            (1,'gudrigues@gmail.com',40),
            (2,'(71)99986-0303', 40),
            (1,'patalmeida@gmail.com',41),
            (2,'(68)98807-0615',41),
            (1,'rafasant@gmail.com',42),
            (2,'(82)99890-5887', 42),
            (1,'didilima@gmail.com',43),
            (2,'(96)99780-3226',43),
            (1,'referr@gmail.com',44),
            (2,'(92)99735-8233', 44),
            (1,'lusonsa@gmail.com',45),
            (2,'(71)99768-8723', 45),
            (1,'masilva@gmail.com',46),
            (2,'(68)99284-6124', 46),
            (1,'tiocelin@gmail.com',47),
            (2,'(82)98895-3905', 47),
            (1,'lariiol@gmail.com',48),
            (2,'(96)99291-1708', 48),
            (1,'vitinro@gmail.com',49),
            (2,'(92)99856-8854', 49),
            (1,'carol.almeida@gmail.com',50),
            (2,'(71)99265-9693', 50);

b) e c) Novo banco de dados para testar a restauração (em caso de falha na restauração o grupo não pontuará neste quesito). <br>
    ![Backup do banco de dados](https://github.com/esthermoraes/Eventando/blob/main/Banco%20de%20dados/eventando.sql?raw=true "Backup do banco de dados")

### 12. PRINCIPAIS CONSULTAS DO SISTEMA <br> 
> Principais consultas (relativas aos 5 principais relatórios) definidas previamente no item 5.3 deste template:
* COLAB: https://colab.research.google.com/drive/1BembJEYM4zWL2QbPSoRckwksGdvLhjTq?usp=sharing
  
### 13. GRÁFICOS, RELATÓRIOS, INTEGRAÇÃO COM LINGUAGEM DE PROGRAMAÇÃO E OUTRAS SOLICITAÇÕES <br>
#### 13.1. INTEGRAÇÃO COM LINGUAGEM DE PROGRAMAÇÃO<br>
#### 13.2. DESENVOLVIMENTO DE GRÁFICOS/RELATÓRIOS PERTINENTES, JUNTAMENTE COM DEMAIS<br>
#### 13.3. OUTRAS SOLICITAÇÕES FEITAS PELO PROFESSOR
> Todos os tópicos se encontram no:
* COLAB: https://colab.research.google.com/drive/1BembJEYM4zWL2QbPSoRckwksGdvLhjTq?usp=sharing

># MARCO DA ENTREGA 02: DO ITEM 1 AO ITEM 13
<br>
 
### 14. SLIDES E APRESENTAÇÃO EM VÍDEO<br>
#### 14.1. SLIDES<br>
* SLIDES: https://www.canva.com/design/DAFmdCF90bE/CgJyX0HK35jwzxr0NvuazQ/view?utm_content=DAFmdCF90bE&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink
#### 14.2. APRESENTAÇÃO EM VÍDEO
* MINI PITCH: https://youtu.be/mhbzkoo9UVM
* PITCH: https://youtu.be/bGv8YS3MXHc
* APRESENTAÇÃO DO SISTEMA: https://youtu.be/SsWORwzUMN4
  
># MARCO DA ENTREGA 03: DO ITEM 1 AO ITEM 14

<br>
--------------------------------------------------------------------------------------------------------------------------------
<br>

##### About Formatting
    https://help.github.com/articles/about-writing-and-formatting-on-github/
    
##### Basic Formatting in Git
    https://help.github.com/articles/basic-writing-and-formatting-syntax/#referencing-issues-and-pull-requests
   
##### Working with advanced formatting
    https://help.github.com/articles/working-with-advanced-formatting/

##### Mastering Markdown
    https://guides.github.com/features/mastering-markdown/

### OBSERVAÇÕES IMPORTANTES

#### Todos os arquivos que fazem parte do projeto (Imagens, pdfs, arquivos fonte, etc..), devem estar presentes no GIT. Os arquivos do projeto vigente não devem ser armazenados em quaisquer outras plataformas.
- Caso existam arquivos com conteúdos sigilosos, comunicar o professor que definirá em conjunto com o grupo a melhor forma de armazenamento do arquivo.

#### Todos os grupos deverão fazer Fork deste repositório e dar permissões administrativas ao usuário deste GIT, para acompanhamento do trabalho.

#### Os usuários criados no GIT devem possuir o nome de identificação do aluno (não serão aceitos nomes como Eu123, meuprojeto, pro456, etc). Em caso de dúvida comunicar o professor.

Link para BrModelo:<br>
http://sis4.com/brModelo/brModelo/download.html <br>

Link para curso de GIT:<br>
![https://www.youtube.com/curso_git](https://www.youtube.com/playlist?list=PLo7sFyCeiGUdIyEmHdfbuD2eR4XPDqnN2?raw=true "Title")
