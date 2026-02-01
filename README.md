# Badges Estáticos com Shields.io

Os **badges estáticos** são indicadores visuais que mostram informação no teu README, como estado de build, cobertura de código, versão ou qualquer texto personalizado. Eles podem ser configurados em **cor, estilo, logo e texto**.

Se tiveres dificuldades de entender essa documentação, eu fiz uma versão web da ferramenta que te ajuda a cria seu badges sem ter que lidar com códigos. Você pode experimentar clicando [aqui](https://nice-readme.vercel.app/badges), ou ver o repositório [aqui](https://github.com/heliocarlitos/nice-readme), a documentação oficial [aqui](https://shields.io/).

## Como Criar Badges Personalizados

### Estrutura Básica da URL

```
https://img.shields.io/badge/<label>-<mensagem>-<cor>?style=<estilo>&logo=<logo>&logoColor=<corLogo>
```

* `<label>`: texto da esquerda
* `<mensagem>`: texto da direita
* `<cor>`: cor da direita (hex, rgb, rgba, hsl, hsla, ou nome CSS)
* `style` (opcional): `flat`, `flat-square`, `plastic`, `for-the-badge`, `social`
* `logo` (opcional): ícone da [Simple Icons](https://simpleicons.org/)
* `logoColor` (opcional): cor do logo

## Exemplos de Badges

### 1. Badge Simples (Label + Mensagem + Cor)

```markdown
![Exemplo](https://img.shields.io/badge/Exemplo-Ativo-brightgreen)
```

![Exemplo](https://img.shields.io/badge/Exemplo-Ativo-brightgreen)

---

### 2. Badge com Mensagem e Cor Apenas

```markdown
![Mensagem](https://img.shields.io/badge/Só%20Mensagem-8A2BE2)
```

![Mensagem](https://img.shields.io/badge/Só%20Mensagem-8A2BE2)

---

### 3. Badge com Estilo `for-the-badge`

```markdown
![Build](https://img.shields.io/badge/Build-Passou-brightgreen?style=for-the-badge)
```

![Build](https://img.shields.io/badge/Build-Passou-brightgreen?style=for-the-badge)

---

### 4. Badge com Logo

```markdown
![GitHub](https://img.shields.io/badge/GitHub-Repositório-000?logo=github&logoColor=white)
```

![GitHub](https://img.shields.io/badge/GitHub-Repositório-000?logo=github\&logoColor=white)

---

### 5. Badge com Label e Cor Personalizadas

```markdown
![Saúde](https://img.shields.io/badge/Saúde-Bom-abcdef?logo=heart)
```

![Saúde](https://img.shields.io/badge/Saúde-Bom-abcdef?logo=heart)

---

### 6. Badge com Cache

```markdown
![Build Cache](https://img.shields.io/badge/Build-Passou-brightgreen?cacheSeconds=3600)
```

![Build Cache](https://img.shields.io/badge/Build-Passou-brightgreen?cacheSeconds=3600)

---

### 7. Badge com Label, Cor e Logo Personalizados

```markdown
![Cobertura](https://img.shields.io/badge/Cobertura-95%25-orange?style=flat-square&logo=appveyor&logoColor=white)
```

![Cobertura](https://img.shields.io/badge/Cobertura-95%25-orange?style=flat-square\&logo=appveyor\&logoColor=white)

---

## Regras de Codificação de URL

| Entrada na URL | Resultado      |
| -------------- | -------------- |
| `_` ou `%20`   | Espaço         |
| `__`           | Underscore `_` |
| `--`           | Hífen `-`      |

---

## Parâmetros Disponíveis

* **style**: `flat`, `flat-square`, `plastic`, `for-the-badge`, `social`
* **color**: cor do fundo da direita (hex, rgb, rgba, hsl, hsla, ou nome CSS)
* **label**: texto da esquerda (URL-encoded se necessário)
* **labelColor**: cor da esquerda
* **logo**: ícone da [Simple Icons](https://simpleicons.org/)
* **logoColor**: cor do logo
* **logoSize**: `auto` para redimensionamento adaptativo
* **cacheSeconds**: tempo de cache HTTP em segundos

---

## Dicas

* Para adicionar **espaços**, usa `%20` ou `_`.
* Para adicionar **hífens**, usa `--`.
* Os badges podem ser usados em **Markdown** ou **HTML**.
* Para links, `<object>` HTML é necessário, `<img>` não suporta `link`.


**Fonte**: [shields.io](https://shields.io/)

Esse projecto está sob licença. Veja o arquivo [LICENÇA](https://github.com/heliocarlitos/badges-estaticos-shields?tab=MIT-1-ov-file) para mais detalhes.

