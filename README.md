# WiMapping

**WiMapping** é uma aplicação web interativa para medir e mapear a velocidade da internet em diferentes cômodos de uma casa. Ela permite realizar testes de velocidade com múltiplos downloads, visualizar os resultados em gráficos e exportar relatórios em PDF.

🔗 **Acesse a aplicação:**  
[https://brenolobao.github.io/WiMapping/](https://brenolobao.github.io/WiMapping/)

---

## 📸 Visão Geral

A interface do WiMapping permite dois modos principais de uso:

- **Teste Normal:** Mede a velocidade da internet com base em múltiplos downloads por rodada.
- **Mapear Casa:** Permite mapear a qualidade da internet em diferentes cômodos, nomeando-os manualmente.

---

## 🚀 Funcionalidades

- **Seleção de Modo de Teste:**  
  - `Teste Normal`: Realiza testes com múltiplas rodadas e downloads por rodada.  
  - `Mapear Casa`: Permite nomear cômodos e medir a velocidade por localização.

- **Gráficos Dinâmicos:**  
  - Gráfico da velocidade de cada download.  
  - Gráfico com a média por rodada geral.

- **Exportação de Relatório:**  
  - Geração de relatório em PDF utilizando `html2canvas` e `jsPDF`.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 / CSS3**
- **JavaScript**
- **Chart.js** – para visualização de gráficos
- **jsPDF** e **html2canvas** – para gerar e exportar o relatório em PDF

---

## 📂 Estrutura do Projeto

```
📁 WiMapping/
├── index.html           # Página principal da aplicação
├── style.css            # Estilos da interface
├── script.js            # Lógica de teste, gráficos e exportação
└── logo.jpg             # Logotipo exibido no topo da página
```

---

## 🎮 Como Usar

1. **Abra o arquivo `index.html` em um navegador** ou acesse o [deploy online](https://brenolobao.github.io/WiMapping/).
2. **Escolha o modo de teste desejado.**
3. **Configure o número de rodadas e downloads.**
4. **Execute os testes e visualize os gráficos.**
5. **(Opcional) Baixe o relatório em PDF após a conclusão.**

---

## 📋 Exemplo de Uso

- **Teste Normal:**  
  Escolha 5 rodadas com 10 downloads cada e clique em “Iniciar Teste”.

- **Mapeamento:**  
  Digite o nome de cada cômodo (ex: "Sala", "Quarto") e clique em “Realizar Teste neste Cômodo”. Após testar todos os locais, clique em “Finalizar Mapeamento”.

---