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
