# Basic Checklist Wordpress Code Review

**Requisitos Básicos**
 - [ ] Arquivos estão organizados corretamente ?
 - [ ] Pull Request formatado da maneira correta ?

**Formatação de código**
 - [ ] O código está formatado corretamente?
 - [ ] O código está seguindo as boas praticas adotada pelo time ?

**Melhores Práticas**
 - [ ] Foi adotado prevenção de erros ao código com validações ?
 - [ ] Nenhum comentário desnecessário ?
 - [ ] Nomes de váriaveis coerentes ao contexto ?
 - [ ] Nomes de funções coerentes ao contexto ?
 - [ ] Os método/funções foram documentados corretamente ?

**Capacidade de manutenção**
 - [ ] O código é fácil de ler (código simplificado)?
 - [ ] Os método/funções não são muito longas ?
 
**Acessibilidade**
 - [ ] O código está seguindo boas práticas de acessibilidade ?
 
 **Semantica**
 - [ ] O HTML está estruturado de maneira semantica ?

**WordPress / Segurança**
 - [ ] O código evita o uso de funções obsoletas do WordPress?
 - [ ] Todas as saídas de dados estão escapadas corretamente para prevenir XSS (esc_html, esc_url, esc_attr, esc_js...)?
 - [ ] Todos os dados de entrada do usuário estão sendo validados e sanitizados?

