[!TIP]
***Relacional***
  Consinte em garantir o relacionamento e consistencia para tal utiliza as propriedade ACID:

  Atomicity   - Reliza a tarefa completa ou não realiza a tarefa
  Consistency - Garante que o dado esteja no banco até que o mesmo seja removido ou alterado
  Isolation   - Apresenta uma caracteristica que uma transação não afetará outra
  Durability  - As informações permanecem por inderteminado tempo.

  Com isso induz a Normalização, para evitar dados duplicado. Mecanismo de busca capaz de aninhar consultas.

  Backup o banco relacional facilita a criação de cópias de segurança identicas a o sistema em produçao desta forma a qualquer momento permite que seja criado uma nova instancia do banco.

[!TIP]
***Não Relacional***
  Por outro lado este utiliza de uma estrutura não rigida, sendo a estrutura maleável/variável. 
  Alta capacidade de processar dados(Big Data) com Escalabilidade Horizontal, preza a Flexibilidade. 
  Sendo indicado para grande volume de dados.
