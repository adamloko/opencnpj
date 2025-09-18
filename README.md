# OpenCNPJ
### WebService para consulta basica de CNPJs com dados totalmente publico!

Uma **API** feita para **ajudar a comunidade de desenvolvedores** a integrar dados de CNPJs de forma rápida e prática.  
Pode ser usado em **qualquer projeto ou aplicação que precise acessar dados de CNPJs**.

---

## 🔹 Ideia do projeto

- **Dados totalmente públicos de CNPJs**, acessíveis de forma simples.
- Integração fácil com **qualquer sistema** que precise desses dados.
- **Limite de 500 requisições por minuto**, para uso consistente sem sobrecarregar o serviço.
- **100% gratuito**, permitindo que a comunidade participe, melhore e reutilize.

---

## 🔹 Como usar

Exemplo de requisição com `curl`:

```bash
curl https://kitana.opencnpj.com/cnpj/12345678000195
```

```json
{
    "success": true,
    "message": null,
    "data": {
        "cnpj": "12.345.678/0001-95",
        "situacaoCadastral": "Ativa",
        "dataSituacaoCadastral": "01/01/2025",
        "motivoSituacaoCadastral": "SEM MOTIVO",
        "razaoSocial": "Mortal Kombat LTDA",
        "nomeFantasia": "Kitana",
        "dataInicioAtividades": "01/01/2020",
        "matriz": "Sim",
        "naturezaJuridica": "Sociedade Empresária Limitada (2062)",
        "capitalSocial": 10,
        "email": "kitana@exemplo.com",
        "telefone": "(62) 1234-5678",
        "logradouro": "Rua subzero, 123",
        "numero": "123",
        "complemento": "Sala 1",
        "bairro": "VILA NOVA",
        "municipio": "GOIANIA",
        "uf": "GO",
        "cep": "01000-000",
    }
}
```

### Os dados são públicos?

Sim! Todos os dados são totalmente públicos e podem ser consultados nos portais oficiais do governo.

### E estão sempre atualizados?

Nos esforçamos para manter tudo atualizado, com revisões mensais sempre que possível.

### Encontrou algum problema?

Abra uma **issue** no GitHub e nos avise. Vamos adorar corrigir!

### Tem sugestões ou ideias?

Mande um chamado ou crie uma issue — seu feedback ajuda muito a melhorar o OpenCNPJ!

### Quer apoiar o projeto?

Dar um ⭐ no GitHub ou contribuir ajuda a manter o OpenCNPJ ativo e disponível para a comunidade.

Obrigado pelo apoio! 🙌

### Quer apoiar ainda mais o projeto?

Se o OpenCNPJ está sendo útil para você e **quiser me pagar uma cerveja 🍺**, você pode contribuir clicando aqui:

### Não é obrigatório, mas qualquer ajuda mantém o projeto ativo e disponível para a comunidade!  
### Também vale dar um ⭐ no GitHub 😉