![Código Certo Coders](https://utfs.io/f/3b2340e8-5523-4aca-a549-0688fd07450e-j4edu.jfif)

# 📚 Trilha Inicial DevOps Jr
Este projeto tem como objetivo principal introduzir e praticar conceitos fundamentais de DevOps Jr através da implementação de um pipeline de CI/CD para uma aplicação web simples. Os principais objetivos são:

**Objetivo:**
Desenvolver um plano de teste simples para o site da comunidade [Código Certo Coders](https://www.codigocertocoders.com.br/). Este desafio ajudará a avaliar o conhecimento básico em testes de software, incluindo planejamento, execução e reporte de testes.

---

### Descrição do Site

O site da comunidade Código Certo Coders oferece aos usuários as seguintes funcionalidades:
1. Visualizar a página inicial com informações sobre a comunidade.
2. Navegar para a página de cursos e visualizar a lista de cursos disponíveis.
3. Inscrever-se em um curso.
4. Acessar a página de contato e enviar uma mensagem.

### Requisitos Funcionais

1. **Página Inicial:**
   - Exibir informações sobre a comunidade.
   - Links de navegação para outras páginas (Cursos, Contato).

2. **Página de Cursos:**
   - Exibir uma lista de cursos com nome, descrição e instrutor.
   - Botão "Inscrever-se" para cada curso.

3. **Inscrição em Curso:**
   - Formulário com campos para nome, e-mail e curso selecionado.
   - Botão "Enviar".

4. **Página de Contato:**
   - Formulário com campos para nome, e-mail e mensagem.
   - Botão "Enviar".

---

### Plano de Teste

#### 1. Objetivo do Teste
Verificar se o site Código Certo Coders funciona conforme os requisitos especificados, garantindo que todas as funcionalidades sejam executadas corretamente e que a experiência do usuário seja satisfatória.

#### 2. Escopo do Teste
Os testes serão realizados nas seguintes funcionalidades:
- Visualização da página inicial
- Navegação para a página de cursos e visualização dos cursos
- Inscrição em um curso
- Navegação para a página de contato e envio de mensagem

#### 3. Tipos de Teste
- Teste Funcional
- Teste de Usabilidade
- Teste de Interface

#### 4. Ambiente de Teste
- Navegadores: Chrome, Firefox, Safari
- Ferramentas: Ferramentas de teste manual, como TestRail ou Excel para gerenciar casos de teste, e ferramentas de captura de tela/vídeo para documentar os testes.

#### 5. Casos de Teste

| ID  | Caso de Teste                                      | Passos                                                                                      | Resultado Esperado                                                  |
|-----|----------------------------------------------------|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------|
| 1   | Visualizar Página Inicial                          | 1. Acessar a página inicial. <br> 2. Verificar as informações exibidas.                      | As informações sobre a comunidade devem ser exibidas corretamente.  |
| 2   | Navegar para a Página de Cursos e Visualizar Cursos | 1. Acessar a página inicial. <br> 2. Clicar no link para a página de cursos. <br> 3. Verificar a lista de cursos. | A lista de cursos deve ser exibida com nome, descrição e instrutor. |
| 3   | Inscrever-se em um Curso                           | 1. Acessar a página de cursos. <br> 2. Clicar em "Inscrever-se" para um curso. <br> 3. Preencher o formulário de inscrição. <br> 4. Clicar em "Enviar". | O formulário deve ser enviado e uma confirmação deve ser exibida.  |
| 4   | Navegar para a Página de Contato e Enviar Mensagem | 1. Acessar a página inicial. <br> 2. Clicar no link para a página de contato. <br> 3. Preencher o formulário de contato. <br> 4. Clicar em "Enviar". | O formulário deve ser enviado e uma confirmação deve ser exibida.  |

#### 6. Critérios de Aceitação
- Todas as funcionalidades devem estar implementadas conforme os requisitos.
- Nenhuma falha crítica deve ser encontrada.
- O site deve ser fácil de usar e navegar.

#### 7. Relatório de Teste
O relatório de teste deve incluir:
- Resumo dos testes realizados.
- Lista de casos de teste executados com os resultados.
- Descrição de qualquer problema encontrado, incluindo passos para reproduzir e gravações de tela ou vídeos se aplicável.

---

### Entrega do Projeto

1. **Documentação:**
   - Um documento contendo o plano de teste detalhado.
   - A lista de casos de teste com resultados esperados e observados.

2. **Relatório de Execução:**
   - Um relatório descrevendo os testes realizados, os resultados, e qualquer problema encontrado.

3. **Envio:**
   - Envie os documentos e relatórios para avaliação.

---

### Dicas para Conclusão

- **Foco nos Detalhes:** Certifique-se de que cada funcionalidade é testada minuciosamente.
- **Documentação Clara:** Mantenha sua documentação clara e organizada para facilitar a leitura e a compreensão.
- **Teste em Diferentes Cenários:** Teste o site em diferentes navegadores e dispositivos para garantir a robustez.

### Dicas para Abordar o Projeto 🌟
- **Crie um Fork desse Repositório.**
- **Criar do Zero:** É fundamental que o projeto seja desenvolvido completamente do zero, demonstrando suas habilidades e criatividade desde o início.
- **Teste o Pipeline localmente antes de subir para o GitHub para garantir que está funcionando corretamente.**

### Critérios de Avaliação:
1. **Configuração do Pipeline:** O pipeline de CI/CD está configurado corretamente e automatiza os processos de build, testes e deploy?
2. **Qualidade do Código:** O código da aplicação e os arquivos de configuração estão bem estruturados e documentados?
3. **Execução dos Testes:** Os testes são executados automaticamente e verificam a funcionalidade da aplicação?
4. **Deploy Automático:** A aplicação é automaticamente implantada em uma plataforma de hospedagem?
5. **Documentação:** A documentação é clara e detalha o processo de configuração e execução do pipeline?

### Não Queremos 🚫
- Descobrir que o candidato não foi quem realizou o teste.
- Ver commits grandes sem muita explicação nas mensagens no repositório.
- Entregas padrão ou cópias de outros projetos. Buscamos originalidade e autenticidade em cada contribuição.

### Prazo ⏳
A data máxima para entrega das trilhas foi removida, permitindo que as pessoas entreguem conforme sua disponibilidade. No entanto, ainda é necessário concluir a trilha com sucesso para ser inserido em uma equipe.

## Checklist de Configuração do Ambiente de Trabalho

**Ferramentas e Plataformas Utilizadas:**
- **Repositório Git:** GitHub
- **Integração Contínua/Entrega Contínua:** GitHub Actions
- **Hospedagem:** Heroku, Netlify, Vercel ou GitHub Pages

**Configuração do Ambiente:**
1. **Criar Conta no GitHub:** Se você ainda não tem uma conta, crie uma conta gratuita no GitHub.
2. **Configurar GitHub Actions:**
   - Crie workflows de CI/CD no diretório `.github/workflows/` do repositório.
3. **Deploy:**
   - Configure uma conta na plataforma de hospedagem escolhida.
   - Integre o deploy com o workflow do GitHub Actions.

### Instruções de Entrega: 📬
Após finalizar o projeto, publique-o em uma URL pública (por exemplo, Vercel, Netlify, GitHub Pages, etc.) e hospede o seu servidor na nuvem. Use serviços que ofereçam uso gratiuto por um período, como a AWS e preencha o [Formulário](https://forms.gle/gZViPMTSDV5nidSu6):  

---

### Desafio da Inovação 🚀
Achou esse projeto inicial simples? Eleve ainda mais! Estamos em busca de mentes inovadoras que não apenas criem, mas que também desafiem os padrões. Como você pode transformar essa estrutura inicial em algo verdadeiramente extraordinário? Demonstre o poder da sua criatividade e o impacto das suas ideias inovadoras!

---

🔗 **Mantenha-se Conectado:**
- [Discord](https://discord.gg/wzA9FGZHNv)
- [Website](http://www.codigocertocoders.com.br/)
- [LinkedIn](https://www.linkedin.com/company/codigocerto/)
  
🌐 **Contato:**
- Email: codigocertocoders@gmail.com

---

### Precisa de Ajuda?
Está com alguma dificuldade, encontrou algum problema no desafio ou tem alguma sugestão pra gente? Crie uma issue e descreva o que achar necessário.

**Construindo o amanhã, hoje.**
