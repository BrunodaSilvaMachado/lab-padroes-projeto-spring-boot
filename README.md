# Padrões de Projeto com Spring boot

## Padrão Criacional

### Singleton

Permitir a craição de uma única instância de uma classe e fornecer um modo para recuprá-la. O singleton é injetado nos componentes do Spring boot com ´@Autowired´.

## Padão Comportamental

### Strategy

Simplificar a variação de algoritmos para a resolução de um mesmo problema. Fazemos o uso do strategy criando ama interface e implementado o serviço dela. Utiliza-se o ´@Service´ para indicar que é um componente Spring boot.
