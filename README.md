# Ecommerce Insights

Dashboard for ecommerce insights

## Technologies

- [ ] Angular
- [ ] Angular Material
- [ ] ngx-charts ou Chart.js
- [ ] JSON Server
- [ ] Firebase Hosting / Vercel para deploy
- [ ] Cypress (opcional) para 1 teste E2E curto

## Requirements

- [ ] Login falso / mock (opcional).
- [ ] Layout com Angular Material (sidebar + topbar).
- [ ] 1 página de métricas com 3 gráficos (ex.: linha, barra, donut).
- [ ] 1 tabela paginada, filtrável e ordenável.
- [ ] Chamada a uma API mock (JSON Server / static JSON) com serviço Angular.
- [ ] Tema claro/escuro toggle.
- [ ] Responsividade básica.

## Schedule

- Dia 1: Setup do projeto Angular + Angular Material + structure; criar repo e README inicial.
- Dia 2: Layout (sidebar, topbar) + responsividade.
- Dia 3: Serviço de dados mock (JSON) e integração.
- Dia 4: Implementar tabela (paginada, filtro).
- Dia 5: Implementar 3 gráficos e integração com dados.
- Dia 6: Tema claro/escuro + polish UI.
- Dia 7: Tests básicos (unit) + deploy (Netlify/Vercel/Firebase Hosting).

## Mock data

```json
{
  "revenue": [
    { "month": "2025-01", "value": 12000 },
    { "month": "2025-02", "value": 15800 },
    { "month": "2025-03", "value": 14200 },
    { "month": "2025-04", "value": 17600 },
    { "month": "2025-05", "value": 19100 }
  ],

  "visits": [
    { "day": "2025-05-01", "count": 220 },
    { "day": "2025-05-02", "count": 310 },
    { "day": "2025-05-03", "count": 280 },
    { "day": "2025-05-04", "count": 350 },
    { "day": "2025-05-05", "count": 400 }
  ],

  "products": [
    {
      "id": 1,
      "name": "Fone Bluetooth X100",
      "price": 299,
      "stock": 45,
      "category": "eletronicos"
    },
    { "id": 2, "name": "Mouse Gamer Pro", "price": 199, "stock": 5, "category": "perifericos" },
    {
      "id": 3,
      "name": "Teclado Mecânico Ultra75",
      "price": 499,
      "stock": 12,
      "category": "perifericos"
    },
    {
      "id": 4,
      "name": "Monitor Full HD 24\"",
      "price": 899,
      "stock": 0,
      "category": "eletronicos"
    },
    { "id": 5, "name": "Cadeira Gamer LX", "price": 1299, "stock": 7, "category": "mobilia" }
  ],

  "orders": [
    {
      "id": 100,
      "productId": 1,
      "amount": 299,
      "quantity": 1,
      "date": "2025-05-02",
      "status": "completed"
    },
    {
      "id": 101,
      "productId": 3,
      "amount": 499,
      "quantity": 1,
      "date": "2025-05-03",
      "status": "completed"
    },
    {
      "id": 102,
      "productId": 2,
      "amount": 199,
      "quantity": 1,
      "date": "2025-05-04",
      "status": "pending"
    },
    {
      "id": 103,
      "productId": 5,
      "amount": 1299,
      "quantity": 1,
      "date": "2025-05-05",
      "status": "completed"
    }
  ],

  "users": [
    { "id": 1, "name": "João Silva", "status": "active", "createdAt": "2024-11-10" },
    { "id": 2, "name": "Maria Souza", "status": "inactive", "createdAt": "2024-11-18" },
    { "id": 3, "name": "Carlos Pereira", "status": "active", "createdAt": "2025-01-05" },
    { "id": 4, "name": "Ana Oliveira", "status": "active", "createdAt": "2025-02-02" }
  ]
}
```
