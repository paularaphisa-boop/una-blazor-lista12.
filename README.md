# 🌱 EcoMonitor

Projeto desenvolvido com Blazor com foco em sustentabilidade, utilizando um componente reutilizável para monitoramento de ações ecológicas.

---

## 🧠 Heurísticas de Nielsen Aplicadas

### ✔️ Visibilidade do Status do Sistema
O componente exibe o **contador atualizado em tempo real** sempre que o usuário interage com o botão.  
Isso permite que o usuário acompanhe imediatamente o resultado de suas ações.

---

### ✔️ Feedback Imediato
Ao clicar no botão, o valor é incrementado instantaneamente.  
Além disso, a **mudança de cor ao atingir a meta (50 pontos)** fornece um feedback visual claro sobre o progresso.

---

### ✔️ Consistência e Padrões
Todos os componentes seguem o mesmo padrão visual e de interação (título, contador e botão), facilitando o uso e aprendizado.

---

## ▶️ Guia de Execução
```bash
📌 1. Criar o projeto
dotnet new blazor -n EcoMonitor
📌 2. Acessar a pasta do projeto
cd EcoMonitor
📌 3. Executar o projeto com HTTPS
dotnet run --launch-profile https
📌 4. Abrir no navegador
https://localhost:7080

⚙️ Explicação Técnica

O [Parameter] é utilizado no Blazor para permitir a comunicação entre componentes, tornando o componente reutilizável.

🧩 Exemplo no componente:
[Parameter]
public string Titulo { get; set; }

[Parameter]
public int Peso { get; set; }

🎯 Benefícios
Reutilização de código
Facilidade de manutenção
Componentização
Maior organização do projeto
