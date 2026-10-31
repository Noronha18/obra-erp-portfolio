# Obra ERP — portfólio

Projeto em desenvolvimento de um ERP para construtoras e incorporadoras de pequeno e médio porte. Primeira etapa: orçamento, execução, compras e financeiro de obras.

Este repositório apresenta a evolução técnica pública do projeto. A implementação operacional é privada. Ainda não há demonstração pública executável aqui.

## Arquitetura

- React e TypeScript para interface responsiva.
- Django e Django REST Framework para regras de negócio e API.
- PostgreSQL para persistência relacional.
- Monólito modular e implantação por containers.
- Preparação para múltiplos clientes, com autorização e isolamento no servidor.

## Estado verificável

A fundação com frontend, backend e PostgreSQL foi implementada e validada em ambiente isolado. Foram exercitados endpoint de saúde, build do frontend, migrações e persistência. Autenticação, empresas e isolamento entre clientes estão em implementação e ainda não são apresentados como recursos aprovados.

Os módulos de orçamento, execução, compras e financeiro permanecem no planejamento. Não há dados reais de clientes, credenciais ou acesso à instalação operacional neste repositório.

## Processo de engenharia

O projeto utiliza desenvolvimento assistido por IA: especificações e planejamento com Astra, implementação com DeepSeek via OpenCode e revisão independente com GPT-6.1 Sol. As decisões, o escopo e a validação de negócio são conduzidos pelo responsável pelo projeto. O uso dessas ferramentas é declarado para tornar o processo transparente.

## Próximas entregas públicas

- Estudo de caso com decisões arquiteturais e limitações.
- Evidências reproduzíveis de testes sobre código demonstrativo publicado.
- Demonstração independente com dados inteiramente fictícios.
- Capturas e instruções de execução quando a versão demonstrativa existir.

Até essas entregas, este é um registro de projeto em andamento, não uma amostra de código executável.
