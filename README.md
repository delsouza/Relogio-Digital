# Relógio Digital

Este código exibe a hora atual em elementos HTML. Ele usa JavaScript para obter a data e hora atual do sistema e atualiza os elementos HTML com as horas, minutos e segundos.

## Como usar
1. Adicione elementos HTML com os id's "horas", "minutos" e "segundos" onde você deseja exibir a hora.
2. Adicione este código JavaScript à sua página.
3. A hora será exibida automaticamente e atualizada a cada 1 segundo.

## Funcionamento
- O código usa a função `new Date()` para obter a data e hora atual do sistema.
- A função `setInterval()` é usada para definir um intervalo de tempo para a execução da função `time()`. Isso permite que a hora seja atualizada automaticamente a cada 1 segundo.
- Antes de exibir a hora, o código verifica se o número de horas, minutos ou segundos é menor que 10 e adiciona um zero à frente, caso seja. Isso garante que a hora seja exibida com formato correto (hh:mm:ss).
- O conteúdo dos elementos HTML é atualizado usando a propriedade `textContent`.

# Notas
- Certifique-se de que o código JavaScript seja adicionado após a criação dos elementos HTML.
- O intervalo de tempo de 1 segundo pode ser alterado alterando o argumento passado para a função `setInterval()`.
- Caso necessário, você pode mudar os id's dos elementos HTML para corresponderem aos usados na sua página.

# Conclusão
Com este código, você pode adicionar facilmente uma exibição de hora atualizada em sua página web. Sinta-se à vontade para personalizá-lo de acordo com as suas necessidades.

