# KPI MEGA Dashboard

Um dashboard interativo para exibição de indicadores de performance (KPIs) do PowerBI com controles de navegação e efeitos de transição.

## 🚀 Funcionalidades

- **Exibição automática** de múltiplos dashboards PowerBI
- **Controles de navegação** (anterior/próximo/pausa)
- **Seleção de intervalo** de tempo (5s a 2min)
- **Efeitos de transição** animados entre dashboards
- **Controles ocultos** que aparecem com movimento do mouse
- **Barra de progresso** visual para tempo restante
- **Design responsivo** para diferentes telas

## 🛠️ Tecnologias

- HTML5
- CSS3 (com animações)
- JavaScript (ES6+)
- PowerBI Embedded

## 📁 Estrutura do Projeto

```
kpi-mega-dashboard/
├── index.html          # Arquivo principal do dashboard
├── README.md           # Documentação do projeto
├── .gitignore          # Arquivos ignorados pelo Git
└── assets/             # Recursos estáticos (se necessário)
```

## 🚀 Como Usar

1. Clone o repositório:
```bash
git clone https://github.com/[seu-usuario]/kpi-mega-dashboard.git
cd kpi-mega-dashboard
```

2. Abra o arquivo `index.html` em seu navegador:
```bash
# Ou simplesmente clique duas vezes no arquivo
open index.html
```

3. Configure as URLs dos dashboards PowerBI no arquivo `index.html`

## ⚙️ Configuração

Para adicionar ou modificar dashboards, edite o array `urls` no arquivo `index.html`:

```javascript
const urls = [
    "https://app.powerbi.com/view?r=...",
    "https://app.powerbi.com/view?r=...",
    // Adicione mais URLs aqui
];
```

## 🎮 Controles

- **Play/Pausa**: Inicia/para a rotação automática
- **Anterior/Próximo**: Navega manualmente entre dashboards
- **Seletor de tempo**: Ajusta o intervalo de exibição
- **Seletor de efeito**: Escolhe a animação de transição

## 🎨 Efeitos Disponíveis

- Fade
- Scale Up/Down
- Rotate (várias direções)
- Flip (várias direções)
- Slide (várias direções)
- Roll In
- Jello
- E muito mais...

## 📱 Compatibilidade

- Chrome/Edge (recomendado)
- Firefox
- Safari
- Navegadores móveis

## 🔧 Personalização

### Alterar tempo padrão
Modifique a variável `panelDuration` no JavaScript:

```javascript
let panelDuration = 120000; // 120 segundos (2 minutos)
```

### Desabilitar controles ocultos
Remova o código relacionado ao `resetInactivityTimer()`.

### Adicionar novos efeitos
Adicione novas classes CSS na seção `<style>`.

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fork o projeto
2. Criar uma branch (`git checkout -b feature/nova-funcionalidade`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/nova-funcionalidade`)
5. Abrir um Pull Request

## 📝 Licença

Este projeto está sob licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👤 Autor

Desenvolvido por Vinícius Santos - Dorgam Dev

## 📞 Suporte

Para suporte ou dúvidas, entre em contato através do GitHub Issues.
