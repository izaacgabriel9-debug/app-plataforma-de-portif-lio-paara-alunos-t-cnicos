# Documento de Requisitos de Software (DRS)

## 1. Introdução

Trata-se de uma plataforma web responsiva para estudantes de cursos técnicos. permitirá que os alunos criem, organizem e compartilhem seus portfólios profissionais de forma simples, rápida e profissional.

### 1.1 Visao Geral

A plataforma funcionará como um "currículo visual e interativo" onde o aluno poderá exibir seus projetos, estágios, habilidades e certificacoes, gerando um link publico que podera ser enviado para recrutadores e empresas 

### 1.2 Objetivos do Sistema
Facilitar a criação de portfólios com modelos prontos 
Ajudar o aluno a se destacar no mercado de trabalho  
Permitir compartilhamento fácil via link
Organizador trabalhos acadêmicos e experiências 

### 1.3 Público Alvo
Estudantes de cursos técnicos (Integrado ou Subsequente).
- Instituições de ensino (Escolas Técnicas).
- Empresas contratantes e recrutadores.


## 2. Escopo do Sistema

### 2.1 Escopo Incluído
- Gestão de Acesso: Sistema de cadastro, login e recuperação de senha para Alunos e Administradores.
​
- Editor de Portfólio: Interface para o aluno inserir dados pessoais, profissionais, projetos, habilidades, estágios e fazer upload de certificados (PDF).
​
- Templates: Biblioteca de modelos prontos de layout para personalização visual.
​
- Publicação: Geração de link público único e visualização de prévia antes de ir ao ar.
​
- Visualização Pública: Página responsiva e otimizada para visitantes, com botões de contato direto.
​
- Painel Administrativo: Gestão de usuários, cursos e visualização de métricas básicas de uso.
​
- Responsividade: Funcionamento completo em dispositivos móveis, tablets e desktops.

### 2.1 Escopo Incluído
Itens que não fazem parte da versão inicial ou estão fora do propósito:
 
- Aplicativo mobile nativo (será uma Web App responsiva).
​
- Editor de código ou ambiente de desenvolvimento integrado.
​
- Sistema de pagamento ou assinatura.
​
- Chat em tempo real entre visitante e aluno.
​
- Integração automática com plataformas externas (ex: importar dados diretamente do GitHub ou LinkedIn).


## 3. Requisitos Funcionaís

### RF00 - Módulo de Autenticação
 
- RF001: Permitir cadastro e login de usuários (Aluno/Admin).
​
- RF002: Recuperação de senha por e-mail.

Módulo do Aluno
 
- RF003: Cadastro de dados pessoais e profissionais.
​
- RF004: Adicionar e gerenciar projetos com mídia (fotos/vídeos) e descrição.
​
- RF005: Listar habilidades técnicas e comportamentais.
​
- RF006: Registro de estágios e experiências.
​
- RF007: Upload de certificados e documentos em PDF.
​
- RF008: Seleção e aplicação de templates de layout.
​
- RF009: Gerar link público único e visualizar prévia do portfólio.

---

## 4. Requisitos Não Funcionais

### RNF00 --

 RN001 - Responsividade: Adaptar-se perfeitamente a diferentes tamanhos de tela (Mobile, Tablet, Desktop).
​
- RN002 - Performance: Carregamento rápido das páginas e otimização de imagens.
​
- RN003 - Segurança: Criptografia de senhas e proteção contra injeção de SQL/XSS.
​
- RN004 - Usabilidade: Interface intuitiva com curva de aprendizado baixa para usuários leigos.
​
- RN005 - Compatibilidade: Suporte aos navegadores modernos (Chrome, Firefox, Edge, Safari).

## 5. Arquitetura Técnica 

### 5.1 Stacks
 Stacks Tecnológicas
 


#### 5.1.1 Stack Backend 

5.1.1 Stack Backend
 
- Linguagem: Node.js (JavaScript/TypeScript) ou PHP
​
- Framework: NestJS, Express ou Laravel
​
- API: RESTful ou GraphQL

#### 5.1.2 Stack Frontend
- Linguagem: HTML5, CSS3, JavaScript/TypeScript
​
- Framework: React, Vue.js ou Angular
​
- Estilização: Tailwind CSS, Bootstrap ou SASS
​
- Responsividade: Layout Flexbox/Grid adaptativo

#### 5.1.7 Banco de Dados
- Tipo: Relacional
​
- Sistema: MySQL ou PostgreSQL

## 6. Modelo de Dados
