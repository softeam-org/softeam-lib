## Como Contribuir

1. **Fork o Repositório**: Crie uma cópia do repositório em sua conta para poder fazer alterações.
2. **Crie uma Branch**: Ao invés de trabalhar diretamente na branch principal, crie uma nova branch para sua contribuição:
   ```bash
   git checkout -b minha-nova-contribuicao
   ```
3. **Faça suas alterações**: Implemente seu componente ou modifique um existente. Lembre-se de seguir as convenções utilizadas e de manter a clareza no código.
4. **Documente suas alterações**: Adicione um README.md no seu componente e atualize a documentação no diretório `/docs`, caso necessário. Certifique-se de que a documentação seja clara e útil para os outros desenvolvedores.
5. **Faça o Commit e Push**: Envie suas alterações para o seu fork:
   ```bash
   git commit -m "Adicionando novo componente ou atualização"
   git push origin minha-nova-contribuicao
   ```
6. **Abra um Pull Request**: No GitHub, abra uma Pull Request para que possamos revisar suas alterações e, se estiverem prontas, integrar ao repositório principal.

## Padrões

- **Código limpo**: Mantenha o código claro e fácil de entender. Use nomes descritivos para funções e variáveis.
- **Documentação**: Inclua exemplos de uso, explicações e instruções claras sempre que necessário.
- Todos os componentes devem seguir a seguinte estrutura:
```
MeuComponente
├── ArquivoFonte1.cs
├── ArquivoFonte2.cs
├── README.md # Documentação de como utilizar o componente, incluindo um exemplo de uso.
```

## Perguntas e Discussões

Se você tiver dúvidas ou precisar de ajuda, sinta-se à vontade para abrir uma nova Issue.

## Licença

Ao contribuir, você concorda que seu código será licenciado sob a mesma licença do repositório original.
