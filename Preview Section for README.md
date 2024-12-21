## 🎮 Preview ao Vivo

Você pode ver uma demonstração ao vivo do dashboard em: [https://seu-usuario.github.io/dashboard-analitico](https://seu-usuario.github.io/dashboard-analitico)

![Dashboard Preview](./docs/images/dashboard-preview.png)

### Dados de Exemplo

O preview utiliza dados de exemplo que demonstram as principais funcionalidades:
- Métricas de vendas dos últimos 12 meses
- Distribuição geográfica de clientes
- Análise de tendências de produtos
- Indicadores de performance (KPIs)

### Como Testar Localmente

Para rodar o preview com dados de exemplo:

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/dashboard-analitico.git

# Entre no diretório
cd dashboard-analitico

# Instale as dependências
npm install

# Ative o modo preview com dados de exemplo
npm run preview
```

### Personalizando o Preview

Você pode personalizar os dados de exemplo editando o arquivo:
```typescript
// src/data/mock-data.ts
export const mockData = {
  sales: [
    { month: 'Jan', value: 4000 },
    { month: 'Feb', value: 3000 },
    // ... outros dados
  ],
  // ... outras métricas
};
```
