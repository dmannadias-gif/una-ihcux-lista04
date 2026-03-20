# Try-Catch e Prevenção de Erros

## O que é Try-Catch?

O `try-catch` é uma estrutura usada na programação para tratar erros (exceções) de forma controlada.

- `try`: contém o código que pode gerar erro
- `catch`: trata o erro caso ele aconteça

### Exemplo (C#)
```csharp
try
{
    int resultado = 10 / 0;
}
catch (Exception e)
{
    Console.WriteLine("Ocorreu um erro!");
}
Como isso se conecta com Prevenção de Erros?

Na área de UX (Experiência do Usuário) e programação, prevenção de erros significa evitar que o usuário tenha problemas ou, se tiver, lidar com isso da melhor forma possível.

💡 Conexão direta:

O try-catch ajuda porque:

✅ Evita que o sistema quebre
✅ Permite mostrar mensagens claras ao usuário
✅ Controla situações inesperadas
✅ Melhora a experiência do usuário (UX)
