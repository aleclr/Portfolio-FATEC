# Alec Lima Rondel

## :speech_balloon: Introdução

<div style="display: flex; justify-content: space-between;">
    <img src="/assets/_1.png" alt="Alec" style="width: 35%;"/>
</div>

> Olá, eu sou o Alec!

<br>

## Contatos

- [GIT](https://github.com/aleclr)
- [LinkedIn](https://www.linkedin.com/in/alecrondel/)

## Meus Principais Conhecimentos

Sou um designer digital formado, com experiência em front-end e UX/UI que complementam perfeitamente a formação em Banco de Dados. Estou aperfeiçoando e expandindo meu conhecimento em diversas linguagens e tecnologias back-end como Java, Python, Spring, Flask, Spark e Pandas, com o objetivo de me tornar um desenvolvedor Full-Stack completo.  

## :card_index_dividers: PORTFOLIO

---

### 1º SEM - Avaliação Democratizada

[Repositório Github](https://github.com/pontopython/api-bd1)

Parceiro acadêmico: [FATEC](https://fatecsjc-prd.azurewebsites.net)

<img src="/assets/api1/fotoapi0.png" alt="PontoPy" style="width: 70%;"/>

> Neste primeiro contato com a metodologia ágil, a FATEC disponibilizou dois professores para realizar a interface de cliente e orientador SCRUM, para garantir que os alunos pudessem ter contato ativo com o cliente e sanar todas as dúvidas, facilitando a experiência e a curva de aprendizado de uma nova metodologia de trabalho.

> O tema do projeto foi a Avaliação 360º, uma técnica de avaliação que visa criar um ambiente de avaliação honesto e abrangente, onde todos os membros de uma equipe podem realizar tanto a autoavaliação quanto a avaliação de seus colegas. Foi criado então um sistema na linguagem Python, que possibilita o login e a criação e controle de toda a estrutura, usuários, equipes, sprints e avaliações.

### :computer: Tecnologias Utilizadas

![Tecnologias](/assets/api1/tecnologias.png)

<br>

- [Python](https://www.python.org) : Linguagem utilizada para o desenvolvimento do projeto.
- [Github](https://github.com) : Plataforma utilizada para gerenciamento do código fonte do projeto.
- [Visual Studio Code](https://code.visualstudio.com) : Software utilizado como ambiente de desenvolvimento.

### Contribuições Pessoais

Para o primeiro semestre, tive a oportunidade de trabalhar a primeira metade do projeto como Product Owner, realizando a interface com o cliente e criando a estrutura do Product Backlog. Na segunda metade do cronograma, pude ter experiência como developer, trabalhando em desenvolver novas funcionalidades e otimizar o código fonte do projeto.

<details>
    <summary>
        Criação do Product Backlog.
    </summary>
    <br>
    Após o Kickoff do projeto, pude trabalhar em conjunto com o cliente e com a equipe para criar o primeiro Backlog do Projeto, levantando os requisitos, e posteriormente transformando os requisitos em User Stories, desenvolvendo as prioridades e as entregas de valor para o projeto.
    <br>
    <img src="/assets/api1/fotoapi6.png" alt="Tela de Consulta de Horas"/>
    <br>
    <img src="/assets/api1/fotoapi7.png" alt="Tela de Consulta de Horas"/>
</details>

<details>
    <summary>
        Desenvolvimento de funcionalidades.
    </summary>
    <br>
    Também tive a oportunidade de desenvolver meu conhecimento, criando novas funcionalidades para a aplicação, como por exemplo melhorar a estrutura de busca, adicionando uma limitação condicional:
    <br>
    <pre>
        <code>
            def generate_members_list(team):
                members = []
                for member in team["members"]:
                    members.append(member)
            return members
        </code>
    </pre>
    <br>
    <pre>
        <code>        
            def student_limitation(student, turma):
                limitation = False
                teams = get_teams_from_turma(turma)
                for team in teams:
                    members = generate_members_list(team)
                    for member in members:    
                        if student["id"] == member["id"]:
                            limitation = True
                            break
            return limitation
        </code>
    </pre>
</details>

### :man_student: Aprendizado

<details>
    <summary>
        :battery: Hard Skills
    </summary>
    <table>
        <tr>
            <td>Github</td>
            <td>Consolidação do entendimento de estrutura de repositórios e código fonte, além de contato com documentação de projetos.</td>
        </tr>
        <tr>
            <td>Python</td>
            <td>Entendimento da linguagem, e de como criar e estruturar um projeto do zero, com funções, módulos e dependências.</td>
        </tr>
        <tr>
            <td>Visual Studio Code</td>
            <td>Contato com a IDE e experiência com trabalho em equipe num mesmo repositório. Estrutura de commits e a importância da estratégia, documentação e colaboração durante o processo de desenvolvimento.</td>
        </tr>
        <tr>
            <td>Scrum</td>
            <td>Primeiro contato com a metodologia ágil, entendimento das funções, do cronograma, das sprints e dos entregáveis.</td>
        </tr>
    </table>
</details>

<br>

<details>
    <summary>
        :speaking_head: Soft Skills
    </summary>
    <table>
        <tr>
            <td>Proatividade</td>
            <td>Foi necessário muita proatividade para assumir uma função desconhecida de Product Owner, compreender a função e a importância da posição, e realizar as tarefas necessárias.</td>
        </tr>
        <tr>
            <td>Comunicação Efetiva</td>
            <td>Essencial para o trabalho com a metodologia ágil, para interagir com os membros da equipe, e ajudar a todos evoluir em conjunto.</td>
        </tr>
        <tr>
            <td>Visão de Negócio</td>
            <td>Primeiro contato com a responsabilidade de compreender as necessidades de um cliente, e como traduzir estas necessidades para requisitos que podem ser desenvolvidos por uma equipe ágil.</td>
        </tr>
    </table>
</details>

---

### 2º SEM - Controle de Jornada

[Repositório Github](https://github.com/aleclr/api-2sem)

Parceiro acadêmico: [2RPnet](https://2rpnet.com.br/)

<p align="center">
  <img src="/assets/api2/fotoapi1.png" alt="Imagem 1" width="45%">
  <img src="/assets/api2/fotoapi4.png" alt="Imagem 2" width="45%">
</p>

> A 2RP possui mais de 20 anos de experiência disponibilizando para o mercado soluções para análise de informações em tempo real, e também análise de transações financeiras e de dados, para geração de insights e o aprimoramento da experiência de seus clientes.

> Nosso parceiro buscava uma ferramenta web que fizesse o controle da jornada de trabalho do colaborador, identificasse e classificasse horas extras, controle das horas extras e sobreavisos. Acesso de administrador para o departamento de RH, gestor para aprovação e lançamento das horas e colaborador para apontar horas extras.

### :computer: Tecnologias Utilizadas

![Tecnologias](/assets/api2/tecnologias.png)

<br>

- [Java](https://www.java.com/pt-BR/) : Linguagem utilizada para o desenvolvimento das funcionalidades back-end e front-end do projeto.
- [JavaFX](https://openjfx.io) : Livraria de Java utilizada para criar o design, a lógica de programação, e renderizar as telas da aplicação.
- [PostgreSQL](https://www.postgresql.org) : Banco de Dados escolhido para a aplicação.

### Contribuições Pessoais

Meu principal papel durante o desenvolvimento deste projeto foi como Desenvolvedor Front-End, onde ajudei transformar o layout pensado pelo Product Owner da equipe em telas funcionais e atraentes, com o uso do SceneBuilder para JavaFX, além de trabalhar na integração de classes do java com o front-end.

<details>
    <summary>
        Criação de layouts com JavaFX.
    </summary>
    <div>
        <img src="/assets/api2/fotoapi6.jpeg" alt="Layout Inicial"/>
        <img src="/assets/api2/fotoapi5.png" alt="SceneBuilder"/>
    </div>
    <br>
    Transformação do layout inicial idealizado pelo Product Owner, após discussões com a equipe.

</details>

<details>
    <summary>
        Integração de tabelas.
    </summary>
    <br>
    Trabalhei desde a criação da tabela e sua classe em Java, até a integração na tela do front-end.
    <br>
    <details>
        <summary>
                Criação da Tabela:
        </summary>
            <pre>
                <code>
                    package frontend.util;
                    import javafx.scene.control.CheckBox;
                    <br>
                    public class TabelaAprova {
                        <br>
                        private String colaborador;
                        private String dataHoraInicial;
                        private String dataHoraFinal;
                        private String cliente;
                        private String tipo;
                        private String totalDeHoras;
                        private CheckBox selecione;
                        <br>
                        public TabelaAprova(String colaborador, String dataHoraInicial, String dataHoraFinal, String cliente, String tipo,
                                String totalDeHoras) {
                            this.colaborador = colaborador;
                            this.dataHoraInicial = dataHoraInicial;
                            this.dataHoraFinal = dataHoraFinal;
                            this.cliente = cliente;
                            this.tipo = tipo;
                            this.totalDeHoras = totalDeHoras;
                            this.selecione = new CheckBox();
                        }
                        <br>
                        public String getColaborador() {
                            return colaborador;
                        }
                        public String getDataHoraInicial() {
                            return dataHoraInicial;
                        }
                        public String getDataHoraFinal() {
                            return dataHoraFinal;
                        }
                        public String getCliente() {
                            return cliente;
                        }
                        public String getTipo() {
                            return tipo;
                        }
                        public String getTotalDeHoras() {
                            return totalDeHoras;
                        }
                        public CheckBox getSelecione() {
                            return selecione;
                        }
                    }
                </code>
            </pre>
    </details>
    <details>
        <summary>
            Código Java para Integração:
        </summary>
        <pre>
            <code>
                    @Override
                    public void initialize(URL url, ResourceBundle resourceBundle){
                        // Verificando acesso para todas as telas
                        VerificaAcesso.verificarAcesso(btnAprovaHora, usuario.getCargo(), NomesArquivosFXML.aprovaHora);
                        VerificaAcesso.verificarAcesso(btnConsultar, usuario.getCargo(), NomesArquivosFXML.consultaHora);
                        VerificaAcesso.verificarAcesso(btnRegistrarHora, usuario.getCargo(), NomesArquivosFXML.registraHora);
                        VerificaAcesso.verificarAcesso(btnCadastra, usuario.getCargo(), NomesArquivosFXML.admin);
                        VerificaAcesso.verificarAcesso(btnEdita, usuario.getCargo(), NomesArquivosFXML.admin);
                        <br>
                        // Para preencher o campo de equipe
                        campoEscolhaEquipe.getItems().addAll(conn.getListaColuna(usuario.getMatricula(),"equipe"));
                        <br>
                        // Dados para Teste
                        ObservableList&lt;TabelaAprova&gt; listaHorasPendentes = FXCollections.observableArrayList();
                        listaHorasPendentes.add(new TabelaAprova("Alec", "12/05/2023 18:00", "12/05/2023 19:00", "Americanas", "Sobreaviso", "01:00"));
                        listaHorasPendentes.add(new TabelaAprova("Pedro", "12/05/2023 18:00", "12/05/2023 20:00", "Apple", "Hora Extra", "02:00"));
                        listaHorasPendentes.add(new TabelaAprova("Lucas", "12/05/2023 18:00", "12/05/2023 18:30", "Americanas", "Sobreaviso", "00:30"));
                        tabela.setItems(listaHorasPendentes);
                        <br>
                        // Atribuição
                        colunaColaborador.setCellValueFactory(new PropertyValueFactory&lt;TabelaAprova, String&gt;("colaborador"));
                        colunaDataHoraInicial.setCellValueFactory(new PropertyValueFactory&lt;TabelaAprova, String&gt;("dataHoraInicial"));
                        colunaDataHoraFinal.setCellValueFactory(new PropertyValueFactory&lt;TabelaAprova, String&gt;("dataHoraFinal"));
                        colunaCliente.setCellValueFactory(new PropertyValueFactory&lt;TabelaAprova, String&gt;("cliente"));
                        colunaTipo.setCellValueFactory(new PropertyValueFactory&lt;TabelaAprova, String&gt;("tipo"));
                        colunaTotalDeHoras.setCellValueFactory(new PropertyValueFactory&lt;TabelaAprova, String&gt;("totalDeHoras"));
                        colunaSelecione.setCellValueFactory(new PropertyValueFactory&lt;TabelaAprova, Checkbox&gt;("selecione"));
                    }
            </code>
        </pre>
    </details>
</details>

### :man_student: Aprendizado

<details>
    <summary>
        :battery: Hard Skills
    </summary>
    <table>
        <tr>
            <td>Java</td>
            <td>Primeiro contato com a linguagem, muito aprendizado a respeito de estrutura de projetos, estrutura de classes e programação orientada a objetos.</td>
        </tr>
        <tr>
            <td>JavaFX / SceneBuilder</td>
            <td>O domínio rápido de um novo software e uma nova maneira de desenvolver layouts de front-end se provou extremamente importante para o sucesso do projeto como um todo.</td>
        </tr>
        <tr>
            <td>PostgreSQL</td>
            <td>Primeiro contato com um banco de dados, conhecimentos de como instalar em uma máquina, acessar o SGBD, e como o banco funciona juntamente com a linguagem SQL.</td>
        </tr>
    </table>
</details>

<details>
    <summary>
        :speaking_head: Soft Skills
    </summary>
    <table>
        <tr>
            <td>Proatividade</td>
            <td>Novamente de extrema importância, para ter coragem e aprender uma plataforma nova e conseguir desenvolver os layouts a tempo das entregas de sprint.</td>
        </tr>
        <tr>
            <td>Entrega de Resultados</td>
            <td>Neste semestre consegui compreender a pressão que existe em cima dos desenvolvedores dentro de uma metodologia ágil, para que todos façam suas entregas e ninguém prejudique o trabalho do outro.</td>
        </tr>
        <tr>
            <td>Trabalho em Equipe</td>
            <td>Foi imperativo desenvolver o senso de trabalho em equipe neste semestre, pois entrei em um time novo e precisei aprender muitas tecnologias novas. Sem o trabalho em equipe como um dos pilares de desenvolvimento pessoal neste processo, não teria sido possível conciliar todas as responsabilidades e ainda ser um bom colega de trabalho.</td>
        </tr>
    </table>
</details>

---

### 3º SEM - Controle de Jornada WEB

[Repositório Github](https://github.com/aleclr/Controle-de-jornada)

Parceiro acadêmico: [2RPnet](https://2rpnet.com.br/)

<p align="center">
  <img src="/assets/api3/fotoapi4.png" alt="Imagem 1" width="45%">
  <img src="/assets/api3/fotoapi2.png" alt="Imagem 2" width="50%">
</p>

> A 2RP possui mais de 20 anos de experiência disponibilizando para o mercado soluções para análise de informações em tempo real, e também análise de transações financeiras e de dados, para geração de insights e o aprimoramento da experiência de seus clientes.

> Nosso parceiro buscava uma ferramenta web que fizesse o controle da jornada de trabalho do colaborador, identificasse e classificasse horas extras, controle das horas extras e sobreavisos. Acesso de administrador para o departamento de RH, gestor para aprovação e lançamento das horas e colaborador para apontar horas extras.

### :computer: Tecnologias Utilizadas

![Tecnologias](/assets/api3/fotoapi5.png)

<br>

- [Java](https://www.java.com/pt-BR/) : Linguagem utilizada para o desenvolvimento das funcionalidades back-end do projeto.
- [Spring](https://spring.io/) : Framework escolhido para melhorar a estrutura e a conexão do projeto com o banco de dados.
- [MySQL](https://www.mysql.com/) : SGBD escolhido para criação e manipulação do banco de dados.
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML), [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) e [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) : Linguagens para o desenvolvimento front-end da aplicação web.
- [SQL](https://aws.amazon.com/pt/what-is/sql/) : Linguagem para realizar as querys dentro do SGBD.
- [JWT](https://jwt.io/) : Tecnologia usada para criptografia e segurança dos dados da aplicação.
- [Figma](https://www.figma.com/) : Aplicação web escolhida para organização da documentação e design do projeto.

### Contribuições Pessoais

Durante o semestre em que o projeto foi desenvolvido, tive a oportunidade de atuar como desenvolvedor front-end, ajudando a transformar o design pensado pelo P.O. em páginas reais da web, além da comunicação entre aplicação e banco de dados. Dentre as funções realizadas estão: a criação das páginas, o trabalho na comunicação dos elementos com o banco de dados, bem como a manipulação e a disposição destes dados.

<details>
    <summary>
        Criação e estilização das páginas.
    </summary>
    <br>
    Com base no protótipo pensado pelo Product Owner, e com a utilização das linguagens HTML e CSS, o desenvolvimento das páginas se         iniciou, e depois de conversas com o cliente e alinhamento de preferências, o design final foi atingido. Após isso pude trabalhar na     implementação do design e na criação das páginas para o projeto. Me utilizando de HTML, CSS e Bootstrap.
    <br>
    <img src="/assets/api3/fotoapi1.png" alt="Tela de Consulta de Horas"/>
    <br>
    - Implementação de todas as decisões de design, paleta de cores, fontes, organização dos dados e o formato da tabela que trará os dados do banco. Responsividade das páginas, conteúdos e menus implementada do zero.
    <br>
    <img src="/assets/api3/fotoapi2.png" alt="Tela de Cadastro de Horas"/>
    <br>
    - Padronização de todas as telas, montagem dos formulários e manipulação dos dados inseridos.
</details>

<br>

<details>
    <summary>
        Menus e conteúdos dinâmicos.
    </summary>
    <img src="/assets/api3/fotoapi3.png" alt="Menus"/>
    <br>
    Criação de funções em JavaScript, capazes de identificar qual tipo de usuário está logado na plataforma, e de acordo com suas permissões, carregar o menu principal e seus conteúdos dinamicamente.

</details>

### :man_student: Aprendizado

<details>
    <summary>
        :battery: Hard Skills
    </summary>
    <table>
        <tr>
            <td>HTML/CSS</td>
            <td>Consolidação das habilidades préviamente desenvolvidas.</td>
        </tr>
        <tr>
            <td>JavaScript</td>
            <td>Conhecimentos em funções e consumo de API's com fetch, buscando informações do banco de dados, e manipulando os dados para serem mostrados no DOM.</td>
        </tr>
        <tr>
            <td>Java</td>
            <td>Noções backend e de programação orientada a objeto, mapeamento de entidades e comunicação com o banco de dados.</td>
        </tr>
        <tr>
            <td>MySQL</td>
            <td>Prática de linguagem SQL, entendimento de modelagem e criação de banco de dados, além da conexão com o banco, e posteriormente com o front-end.</td>
        </tr>
        <tr>
            <td>Scrum</td>
            <td>Vivência da metodologia ágil, criação e priorização de tasks, organização de código e de repositórios.</td>
        </tr>
    </table>
</details>

<br>

<details>
    <summary>
        :speaking_head: Soft Skills
    </summary>
    <table>
        <tr>
            <td>Proatividade</td>
            <td>Importante para ter oportunidades de aprender coisas novas, e realizar tarefas que inicialmente não seria possível.</td>
        </tr>
        <tr>
            <td>Comunicação Efetiva</td>
            <td>Essencial para o trabalho com a metodologia ágil, para interagir com os membros da equipe, e ajudar a todos evoluir em conjunto.</td>
        </tr>
        <tr>
            <td>Visão de Negócio</td>
            <td>Desenvolver a habilidade de visão de negócio é extremamente importante, para poder entender as necessidades do cliente, e por consequência entender o valor que cada funcionalidade possui dentro do projeto.</td>
        </tr>
        <tr>
            <td>Inteligência Emocional</td>
            <td>Habilidade necessária para identificar e prevenir conflitos antes deles acontecerem, e conseguir lidar com os conflitos que inevitavelmente surgem em um ambiente de pressão e entrega.</td>
        </tr>
        <tr>
            <td>Mentoria</td>
            <td>Tive a oportunidade de desenvolver bastante a habilidade de mentoria, ao trabalhar em conjunto com um colega no desenolvimento Front-End, e passar para ele bastante do conhecimento que eu já possuía.</td>
        </tr>
    </table>
</details>

---

### 4º SEM - Sistema de Análise de Parceiros ORACLE

[Repositório Github](https://github.com/aleclr/OraclePartnerTracker)

Parceiro acadêmico: [Oracle](https://www.oracle.com)

<p align="center">
  <img src="/assets/api4/fotoapi2.png" alt="Imagem 2" width="100%">
</p>

> A Oracle está a décadas no mercado de tecnologia, e é uma das pioneiras em oferecer serviço de banco de dados e ambientes em nuvem. Nos buscou para uma aplicação web que permita a análise e o controle do seu programa de parceria.

### :computer: Tecnologias Utilizadas

![Tecnologias](/assets/api4/tecnologias2.png)

- [Java](https://www.java.com/pt-BR/) : Linguagem utilizada para o desenvolvimento das funcionalidades back-end do projeto.
- [Spring](https://spring.io/) : Framework escolhido para melhorar a estrutura e a conexão do projeto com o banco de dados.
- [MySQL](https://www.mysql.com/) : SGBD escolhido para criação e manipulação do banco de dados.
- [VueJS](https://vuejs.org) : Framework para criação da estrutura e desenvolvimento da parte web da nossa aplicação.
- [Vuetify](https://vuetifyjs.com/en/) : Biblioteca para complementar o VueJS com funções e componentes mais estéticos e otimizados.
- [Hibernate](https://hibernate.org) : Framework para mapear o banco de dados e fazer a integração com o back-end.

### Contribuições Pessoais

Desempenhei a função de desenvolvedor full-stack neste projeto, trabalhando em diversas tarefas como mapeamento de tabelas do banco de dados, criação de lógica no back-end, criação de controllers e endpoints para recebimento e postagem de dados, criação e implementação de layouts no front-end, estilização de páginas e lógica de programação no front-end com javascript.

<details>
    <summary>
        Mapeamento de tabela
    </summary>
    <br>
    DTO:
    <pre>
        <code>
            package Oracle.Partner.Tracker.dto;
            import Oracle.Partner.Tracker.utils.IngestionOperation;
            import lombok.AllArgsConstructor;
            import lombok.Data;
            import lombok.NoArgsConstructor;
            <br>
            @Data
            @AllArgsConstructor
            @NoArgsConstructor
            public class CertificationDTO implements GenericDTO {
                <br>
                private String name;
                private String description;
                private IngestionOperation ingestionOperation;
                <br>
            }
        </code>
    </pre>
    <br>
    Repository:
    <pre>
        <code>
        package Oracle.Partner.Tracker.repositories;
        import org.springframework.data.jpa.repository.JpaRepository;
        import Oracle.Partner.Tracker.entities.Certification;
        <br>
        public interface CertificationRepository extends JpaRepository<Certification, Long> {
            //
        }
        </code>
    </pre>
</details>

<details>
    <summary>
        Lógica Back-end:
    </summary>
    <br>
    Service:
    <pre>
        <code>
            package Oracle.Partner.Tracker.services;
            import java.util.List;
            import java.util.Optional;
            import java.util.stream.Collectors;
            import org.springframework.beans.factory.annotation.Autowired;
            import org.springframework.stereotype.Service;
            import Oracle.Partner.Tracker.dto.CertificationDTO;
            import Oracle.Partner.Tracker.entities.Certification;
            import Oracle.Partner.Tracker.repositories.CertificationRepository;
            <br>
            @Service
            public class CertificationService {
                <br>
                @Autowired
                private CertificationRepository certificationRepository;
                public List<CertificationDTO> getAllCertifications() {
                    List<Certification> certifications = certificationRepository.findAll();
                    return certifications.stream().map(this::convertToDto).collect(Collectors.toList());
                };
                <br>
                private CertificationDTO convertToDto(Certification certification) {
                    CertificationDTO dto = new CertificationDTO();
                    dto.setName(certification.getName());
                    dto.setDescription(certification.getDescription());
                    dto.setIngestionOperation(certification.getIngestionOperation());
                    return dto;
                };
                <br>
                public CertificationDTO getCertificationById(Long id) {
                    Optional<Certification> certification = certificationRepository.findById(id);
                    return certification.map(this::convertToDto).orElse(null);
                };
                <br>
            }
        </code>
    </pre>
</details>

<details>
    <summary>
        Controller e Endpoints
    </summary>
    <br>
    <pre>
        <code>
            package Oracle.Partner.Tracker.controllers;
            import java.util.List;
            import org.springframework.beans.factory.annotation.Autowired;
            import org.springframework.http.HttpStatus;
            import org.springframework.http.ResponseEntity;
            import org.springframework.web.bind.annotation.CrossOrigin;
            import org.springframework.web.bind.annotation.GetMapping;
            import org.springframework.web.bind.annotation.PathVariable;
            import org.springframework.web.bind.annotation.RequestMapping;
            import org.springframework.web.bind.annotation.RestController;
            import Oracle.Partner.Tracker.dto.CertificationDTO;
            import Oracle.Partner.Tracker.services.CertificationService;
            <br>
            @CrossOrigin
            @RestController
            @RequestMapping(value = "/certification")
            public class CertificationController {
                <br>
                @Autowired
                private CertificationService certificationService;
                <br>
                @GetMapping
                public List<CertificationDTO> getAllCertifications() {
                    return certificationService.getAllCertifications();
                };
                <br>
                @GetMapping("/{id}")
                public ResponseEntity<CertificationDTO> getCertificationById(@PathVariable Long id) {
                    CertificationDTO dto = certificationService.getCertificationById(id);
                    if (dto != null) {
                        return ResponseEntity.ok(dto);
                    } else {
                        return ResponseEntity.status(HttpStatus.NOT_FOUND).build();
                    }
                };
            }
        </code>
    </pre>
</details>

<details>
    <summary>
        Criação e implementação de filtro para tabela
    </summary>
    <br>
    Criação do filtro:
    <pre>
        <code>
            const sortedWorkloadNames = computed(() => {
                return ['Visualizar todas workloads', ...Object.keys(workloadData.value).sort((a, b) => a.localeCompare(b))];
            });
            <br>
            const tableItems = computed(() => {
                let items = Object.keys(workloadData.value).map(workloadName => ({
                    workloadName,
                    companyNames: workloadData.value[workloadName]
            }));
            <br>
            if (selectedWorkload.value !== 'Visualizar todas workloads') {
                items = items.filter(item => item.workloadName === selectedWorkload.value);
            }
            if (partnerFilter.value === 'Workloads com parceiros aptos') {
                items = items.filter(item => item.companyNames.length > 0);
            } else if (partnerFilter.value === 'Workloads sem parceiros aptos') {
                items = items.filter(item => item.companyNames.length === 0);
            }
                return items.sort((a, b) => a.workloadName.localeCompare(b.workloadName));
            });
        </code>
    </pre>
    <br>
    Implementação do filtro:
    <pre>
        <code>
            &lt;VRow&gt;
                &lt;VCol cols="6"&gt;
                    &lt;VSelect
                        class="filtro"
                        v-model="selectedWorkload"
                        :items="sortedWorkloadNames"
                        label="Select Workload"
                        dense
                    /&gt;
                &lt;/VCol&gt;
                &lt;VCol cols="6"&gt;
                    &lt;VSelect
                        class="filtro"
                        v-model="partnerFilter"
                        :items="['Visualizar todos', 'Workloads com parceiros aptos', 'Workloads sem parceiros aptos']"
                        label="Filtrar por Parceiros"
                        dense
                    /&gt;
                &lt;/VCol&gt;
            &lt;/VRow&gt;
        </code>
    </pre>
</details>

<details>
    <summary>
        Funcionalidade front-end de CRUD para certificações
    </summary>
    <br>
    <img src="/assets/api4/fotoapi5.png" alt="Tela de Formulário"/>
    <img src="/assets/api4/fotoapi3.png" alt="Tabela com todas as Certificações"/>
</details>

<details>
    <summary>
        Criação do Logotipo OraclePartnerTracker
    </summary>
    <br>
    <img src="/assets/api4/fotoapi1.png" alt="Menus"/>
</details>

<details>
    <summary>
        Desenvolvimento da funcionalidade de vencimento
    </summary>
    <br>
    <img src="/assets/api4/fotoapi4.png" alt="Menus"/>
</details>

### :man_student: Aprendizado

<details>
    <summary>
        :battery: Hard Skills
    </summary>
    <table>
        <tr>
            <td>Springboot</td>
            <td>Por ter sido um desenvolvedor full-stack neste semestre, pude ter mais contato com o banco de dados e o back-end do nosso projeto, e pude aprender de fato como o springboot consegue estruturar o back-end de um projeto de maneira sólida e modular.</td>
        </tr>
        <tr>
            <td>SQL</td>
            <td>Também tive a oportunidade de evoluir meus conhecimentos em SQL, criando queries na prática, testanto, e as utilizando na criação de endpoints para o nosso RestAPI.</td>
        </tr>
        <tr>
            <td>VueJS</td>
            <td>Primeira experiência com VueJS e com o conceito de componentização dos elementos do front-end, foi desafiador aprender uma estrutura e tecnologia nova em tão pouco tempo, mas com ajuda dos professores e colegas de equipe, foi uma ótima experiência.</td>
        </tr>
    </table>
</details>

<details>
    <summary>
        :speaking_head: Soft Skills
    </summary>
    <table>
        <tr>
            <td>Colaboração</td>
            <td>A partir deste ponto, os projetos e soluções desenvolvidas começaram a ficar mais robustos e com mais funcionalidades, e a colaboração entre todos os membros da equipe se mostrou crucial para o andamento do projeto, tanto pela parte de código quanto pela parte de documentação e processos ágeis.</td>
        </tr>
        <tr>
            <td>Autonomia</td>
            <td>Como desenvolvedor full-stack, tive contato com tecnologias, linguagens e frameworks que nunca havia trabalhado antes, em todas as áreas da nossa aplicação, e isso exigiu muita autonomia para aprender como tudo funciona com rapidez e eficiência, e conseguir ser útil e produtivo ao longo de todas as sprints.</td>
        </tr>
        <tr>
            <td>Feedback Construtivo</td>
            <td>Com a complexidade dos sistemas desenvolvidos aumentando, aumenta também a responsabilidade de cada desenvolvedor, e corre o risco de desentendimentos e brigas internas a respeito da diferença na metodologia pessoal de trabalho de cada colega. O feedback positivo é essencial para manter o bom espírito e a positividade como uma equipe.</td>
        </tr>
    </table>
</details>

---

### 5º SEM - Análise de Dados Para Recrutamento e Processo Seletivo

[Repositório Github](https://github.com/bytelabss/ByteLabss-API5sem)

Parceiro acadêmico: [Pro4Tech](https://pro4tech.com.br)

<p align="center">
  <img src="/assets/api5/fotoapi1.png" alt="Imagem 2" width="100%">
</p>

> A Pro4Tech nos procurou, buscando uma solução para gerenciamento e análise de dados envolvendo seus processos seletivos e de recrutamento. A solução montada pela nossa equipe foi uma plataforma online, capaz de otimizar a maneira como os dados de recrutamento são coletados, visualizados e analisados.

### :computer: Tecnologias Utilizadas

![Tecnologias](/assets/api5/tecnologias.png)

- [Java](https://www.java.com/pt-BR/) : Linguagem utilizada para o desenvolvimento das funcionalidades back-end do projeto.
- [Spring](https://spring.io/) : Framework escolhido para melhorar a estrutura e a conexão do projeto com o banco de dados.
- [MySQL](https://www.mysql.com/) : SGBD escolhido para criação e manipulação do banco de dados.
- [VueJS](https://vuejs.org) : Framework para criação da estrutura e desenvolvimento da parte web da nossa aplicação.
- [Spark](https://spark.apache.org) : Framework para processamento de dados, usado no back-end para melhor análise e manuseio de dados.
- [Docker](https://www.docker.com) : Plataforma para criar e executar contêineres, usado para padronizar os ambientes e implementar DevOps.

### Contribuições Pessoais

Também fiz parte da equipe como um desenvolvedor full-stack neste projeto, onde pude trabalhar em tarefas como mapeamento de tabelas no back-end, criação de lógica para exportação de dados via pdf, query JPA e endpoint relacionado, e a funcionalidade de visualização de queries customizadas no front-end.

<details>
    <summary>
        Mapeamento de tabela
    </summary>
    <br>
    <pre>
        <code>
package fatec.bytelabss.api.models;
import java.time.LocalDateTime;
import jakarta.persistence.*;
import lombok.AllArgsConstructor;Add commentMore actions
import lombok.Data;
import lombok.NoArgsConstructor;
-
@Entity
@Table(name = "PDF_REPORT_LOGS")
@Data
@NoArgsConstructor
@AllArgsConstructor
public class PdfReportLogs {
    @Id
    @GeneratedValue(strategy = GenerationType.IDENTITY)
    @Column(name = "id")
    private Long id;
    -
    @Column(name = "report_date", nullable = false)
    private LocalDateTime reportDate;
    -
    @Column(name = "generated_at", nullable = false)
    private LocalDateTime generatedAt;
    -
    // public PdfReportLog(LocalDateTime reportDate) {
    //     this.reportDate = reportDate;
    //     this.generatedAt = LocalDateTime.now();
    // }
    -
}
        </code>
    </pre>
</details>

<details>
    <summary>
        Exportação de PDF:
    </summary>
    <br>
    Repository:
    <pre>
        <code>
public interface PdfReportLogRepository extends JpaRepository<PdfReportLogs, Long> {
    @Query(nativeQuery = true, value = "SELECT * FROM pdf_report_logs p WHERE p.report_date >= :weekStart")
    }
        </code>
    </pre>
    Service:
    <pre>
        <code>
@Service
public class PdfReportLogService {
    -
    @Autowired
    private PdfReportLogRepository pdfReportLogRepository;
    -
    @Autowired
    private RestTemplate restTemplate;
    -
    private static final String PDF_EXPORT_URL = "http://localhost:9090/api/pdf/export/pdf/zip";
    -
    private static final String DEFAULT_ZIP_FILE_PATH = "relatorios/";
    -
    @Autowired
    public PdfReportLogService(PdfReportLogRepository pdfReportLogRepository, RestTemplate restTemplate) {
        this.pdfReportLogRepository = pdfReportLogRepository;
        this.restTemplate = restTemplate;
    }
    -
    public void generateWeeklyPdfReport() {
        try {
            -
            ResponseEntity<byte[]> response = restTemplate.getForEntity(PDF_EXPORT_URL, byte[].class);
            -
            if (response.getStatusCode() == HttpStatus.OK) {
                byte[] zipData = response.getBody();
                -
                String zipFileName = "weekly_report_" + LocalDate.now() + ".zip";
                -
                saveZipFileLocally(zipData, zipFileName);
                -
                PdfReportLogs log = new PdfReportLogs();
                pdfReportLogRepository.save(log);
                -
                System.out.println("Weekly PDF report generated and saved successfully.");
            } else {
                System.err.println("Failed to generate or download the PDF report. Status code: " + response.getStatusCode());
            }
        } catch (Exception e) {
            System.err.println("Error generating or downloading the PDF report: " + e.getMessage());
        }
    }
    -
    private void saveZipFileLocally(byte[] zipData, String fileName) throws IOException {
        -
        // Use a default or custom path to save the ZIP file
        String filePath = Paths.get(DEFAULT_ZIP_FILE_PATH, fileName).toString();
        -
        // Ensure that the folder exists
        java.nio.file.Files.createDirectories(Paths.get(DEFAULT_ZIP_FILE_PATH));
        -
        // Write the ZIP file to the specified path
        try (FileOutputStream fileOutputStream = new FileOutputStream(filePath)) {
            fileOutputStream.write(zipData);
        }
        -
        System.out.println("ZIP file saved locally at: " + filePath);
    }
    -
    private boolean isCurrentWeekReportGenerated() {
        LocalDate startOfWeek = LocalDate.now().with(TemporalAdjusters.previousOrSame(java.time.DayOfWeek.SUNDAY));
        Optional<PdfReportLogs> reportLog = pdfReportLogRepository.findReportByWeekStart(startOfWeek);
        return reportLog.isPresent();
    }
    -
    @PostConstruct
    public void checkAndGenerateReportOnStartup() {
        if (!isCurrentWeekReportGenerated()) {
            generateWeeklyPdfReport();
        }
    }

}
</code>

</pre>

</details>

<details>
    <summary>
        Query JPA + Endpoint
    </summary>
    <br>
    JPA Query:
    <pre>
        <code>
@Query("SELECT DISTINCT dc.nome AS nomeCandidato, dp.nome AS nomeProcesso " +
      "FROM DimCandidato dc " +
      "JOIN FatoAvaliacoes fa ON dc.idCandidato = fa.candidato " +
      "JOIN DimVaga dv ON fa.vaga = dv.idVaga " +
      "JOIN FatoContratacoes fc ON dv.idVaga = fc.vaga " +
      "JOIN DimProcessoSeletivo dp ON fc.processoSeletivo = dp.idProcessoSeletivo " +
      "WHERE (:candidato IS NULL OR dc.nome = :candidato)")
   List<Object[]> processosPorCandidato(@Param("candidato") String candidato);
        </code>
    </pre>
    <br>
    Endpoint: 
    <pre>
        <code>
    @GetMapping("/processos-por-candidato")
    public ResponseEntity<List<CandidatoProcessoDTO>> getProcessosPorCandidato(@RequestParam(required = false) String candidato) {
        List<CandidatoProcessoDTO> result = service.getProcessosPorCandidato(candidato);
        return ResponseEntity.ok().body(result);
    }
        </code>
    </pre>
</details>

<details>
    <summary>
        Visualização de dados de queries customizadas no Front-End
    </summary>
    <br>
    <img src="/assets/api5/fotoapi2.png" alt="Visualização de Query"/>
    <br>
    Componentes:
    <pre>
        <code>
            <!-- Modal Window Component -->
            &lt;GerarDashboardCustomizado
                v-if="showModal"
                :title="'Criar Análise'"
                :isVisible="showModal"
                :selects="selectOptions"
                @close="showModal = false"
                @submitFormData="handleFormSubmit"
            /&gt;
            -
            <!-- Render the DynamicChart after submission -->
            &lt;div v-if="customQueryCharts.length" class="customquery-charts"&gt;
            &lt;h3&gt;Análises Personalizadas:&lt;/h3&gt;
            &lt;div v-for="(chart, index) in customQueryCharts" :key="index"&gt;
                &lt;CustomQueryChart
                :chartType="chart.chartType"
                :chartData="chart.chartData"
                :chartId="chart.chartId"
                /&gt;
            &lt;/div&gt;
            &lt;/div&gt;
        </code>
    </pre>
    Lógica:
    <pre>
        <code>
    function handleFormSubmit({ transformedData, visualizationModel }) {
    console.log("Form Submitted with Data:", transformedData);
    // Process form data as needed, e.g., save it, send it to an API, etc.
    -
    axios
    .post(`${import.meta.env.VITE_BASE_API_URL}/custom-queries`, transformedData)
    .then((response) => {
    -
      console.log('Query customizada inserida no banco com sucesso! ', response.data);
    -
      const newQuery = response.data;
      const customQueryURL = `${import.meta.env.VITE_BASE_API_URL}/custom-queries/${newQuery.id}/results`;
    -
      queries.value.unshift({
        id: newQuery.id,
        query: transformedData.query,
        description: transformedData.description,
        createdAt: newQuery.createdAt,
      });
    -
      expandedRows.value.unshift(false);      
    -
      axios.get(customQueryURL)
      .then((response) => {
        -
        console.log('Resultado da query customizada: ', response.data);
        -
        const chartData = transformResponseToChartData(response.data);
        console.log('ChartData array gerado: ', chartData)
        -
        // RENDERIZAR RESULTADO EM JSON NA PÁGINA PARA TESTES 
        // queryResults.value.unshift({
        //     queryId: newQuery.id,
        //     data: response.data
        //   });
        -
        customQueryCharts.value.push({
          chartType: visualizationModel || "pie",
          chartData: chartData, // Default data
          chartId: `chart-${customQueryCharts.value.length + 1}`,
        });
      })
      .catch((error) => {
        console.error('Erro ao executar a custom query: ', error);
      });
    -
    })
    .catch((error) => {
      // Handle any errors from the request
      console.error('Erro ao postar a query customizada: ', error);
    });
  }
        </code>
    </pre>
</details>

### :man_student: Aprendizado

<details>
    <summary>
        :battery: Hard Skills
    </summary>
    <table>
        <tr>
            <td>Springboot</td>
            <td>Continuei os aprendizados com o framework springboot, podendo compreender na totalidade a estruturação de projetos, e as vantagens de utilizá-lo.</td>
        </tr>
        <tr>
            <td>Spark</td>
            <td>Trabalhei com o spark pela primeira vez durante este projeto, e tive a oportunidade de entender a importância de frameworks e livrarias de manipulação e visualização de dados no back-end, e sua comunicação com os bancos de dados.</td>
        </tr>
        <tr>
            <td>DevOps</td>
            <td>O grande diferencial deste semestre foi a apresentação do conceito de DevOps, o processo e suas partes. Além de ter um panorâma completo de toda a pipeline de DevOps, tive a oportunidade de aprender e implementar na prática a área de rastreamento de requisitos.</td>
        </tr>
    </table>
</details>

<details>
    <summary>
        :speaking_head: Soft Skills
    </summary>
    <table>
        <tr>
            <td>Trabalho em Equipe</td>
            <td>O trabalho em equipe é essencial em todos os projetos, mas especificamente nesse, por conta do DevOps. Cada integrante do grupo ficou responsável por uma área, e foi preciso mais comunicação e trabalho em equipe para que todas as partes do DevOps pudessem ser implementadas de maneira integrada.</td>
        </tr>
        <tr>
            <td>Responsabilidade</td>
            <td>Por ter sido um projeto grande, com várias etapas e várias entregas, tanto dentro da aplicação quanto fora. Precisei ter e aprender um senso de responsabilidade novo, pois muitas vezes a nota não só minha mas também da equipe como um todo dependia das minhas entregas.</td>
        </tr>
    </table>
</details>

---

### 6º SEM - DataForest: Gerenciamento e Predição em Processos de Reflorestamento

[Repositório Github](https://github.com/bytelabss/ByteLabs-API6Sem)

Parceiro acadêmico: [Kersys](https://www.kersys.com.br)

<p align="center">
  <img src="/assets/api6/fotoapi1.png" alt="Imagem 2" width="100%">
</p>

> O objetivo deste API foi a utilização de machine learning para ajudar o processo de reflorestamento dos clientes da empresa parceira Kersys. A utilização de tecnologias, com exceção do banco de dados MongoDB, ficou à critério das equipes, caracterizando um projeto liberal e diferente dos demais.

### :computer: Tecnologias Utilizadas

![Tecnologias](/assets/api6/tecnologias.png)

- [Python](https://www.python.org) : Linguagem utilizada para o desenvolvimento das funcionalidades back-end do projeto.
- [Flask](https://flask.palletsprojects.com/en/stable/) : Framework escolhido para prover estrutura e a conexão do projeto com o banco de dados.
- [MongoDB](https://www.mongodb.com) : Banco de dados para os dados da aplicação.
- [PostgreSQL](https://www.postgresql.org) : Banco de dados para os dados ambientais retirados de uma base de dados real.
- [Pandas](https://pandas.pydata.org) : Utilizado para manipular e analisar dados no python em larga escala.
- [React](https://react.dev) : Para o front-end do projeto.
- [Typescript](https://www.typescriptlang.org) : Para combinar com o React e fornecer um Javascript mais organizado e robusto.
- [Scikit-learn](https://scikit-learn.org/stable/) : Uma das formas mais populares de se criar machine learning no Python.

### Contribuições Pessoais

Este projeto foi minha primeira experiência trabalhando como Scrum Master, completando assim pelo menos um semestre trabalhando em todas as funções da metodologia SCRUM. Pude aprender bastante de como gerenciar um time de desenvolvedores, e como fazer a ponte entre equipe e P.O, além de também trabalhar na parte de machine learning do projeto.

<details>
    <summary>
        Organização de README e Wiki do projeto
    </summary>
    <br>
    <img src="/assets/api6/fotoapi2.png" alt="Readme"/>
    <br>
    
    Ao criar o repositório, o readme, a organização e a página do projeto no Jira, 
    pude compreender a importância de uma boa organização durante a fase de planejamento e estruturação, 
    antes mesmo do início do desenvolvimento.
</details>

<details>
    <summary>
        Criação do Design Front-End do projeto
    </summary>
    <br>
    <img src="/assets/api6/fotoapi1.png" alt="Home"/>
    <br>
    
    Tomei a iniciativa de fazer o design inicial da aplicação, 
    optei por uma estética mais moderna, com imagens, 
    e cores um pouco mais quentes para remeter a natureza.
</details>

<details>
    <summary>
        Desenvolvimento de um modelo de machine learning
    </summary>
    <br>
    <p align="center">
        <img src="/assets/api6/fotoapi3.png" alt="ML1" width="45%"/>
        <img src="/assets/api6/fotoapi4.png" alt="ML2" width="45%"/>
    </p>
    <br>
    
    Consegui trazer os conceitos das aulas sobre Machine Learning, e aplicá-los,
    para constuir um modelo capaz de classificar áreas geográficas em diferentes estratégias de plantio e manejo, 
    uma das entregas de mais valor para o cliente durante o projeto.
</details>

### :man_student: Aprendizado

<details>
    <summary>
        :battery: Hard Skills
    </summary>
    <table>
        <tr>
            <td>Python</td>
            <td>Embora já havia trabalhado com python nos primeiros semestres do curso, os projetos não eram robustos e complexos. Agora, revisitando a linguagem, pude ter uma nova visão, de como os projetos mais parecidos com os do mercado de trabalho são formados.</td>
        </tr>
        <tr>
            <td>Flask</td>
            <td>Muitas familiaridades com outros frameworks estruturais para back-end (exemplo: Spring) fizeram a curva de aprendizado do Flask ser mais amigável, porém também foi necessário aprender rápido.</td>
        </tr>
        <tr>
            <td>Machine Learning</td>
            <td>Pra mim a parte mais divertida e inovadora deste semestre. Tive a oportunidade de participar do desenvolvimento de um dos modelos de Machine Learning desenvolvidos para o projeto Data Forest, uma experiência desafiadora, porém muito recompensadora.</td>
        </tr>
    </table>
</details>

<details>
    <summary>
        :speaking_head: Soft Skills
    </summary>
    <table>
        <tr>
            <td>Gerência</td>
            <td>Precisei aprender como cuidar da gerencia de uma equipe para exercer o papel de Scrum Master, como realizar as reuniões diárias, como manter o controle das tarefas e da produtividade de todos os integrantes, e como facilitar a produção e o desenvolvimento como um todo.</td>
        </tr>
        <tr>
            <td>Trabalho sob pressão</td>
            <td>Este semestre nosso grupo estava com poucos integrantes, por diversos motivos. Contamos com apenas 3 desenvolvedores, o que deixou a equipe num geral pressionada e estressada. Precisei aprender a lidar com a pressão, ajudar os companheiros, e a realizar múltiplas funções quando necessário.</td>
        </tr>
    </table>
</details>
