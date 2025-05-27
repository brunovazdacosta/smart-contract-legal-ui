# smart-contract-legal-ui
"Interface web para simulação de pagamento de contrato jurídico com cláusula de multa por atraso"
git clone https://github.com/brunovazdacosta/smart-contract-legal-ui.git
cd smart-contract-legal-ui
smart-contract-legal-ui/
├── frontend/            # Aplicação React + Vite + Tailwind + ethers.js
│   ├── src/
│   │   ├── components/  # Componentes da interface (ContratoInfo, PagamentoForm)
│   │   ├── App.jsx
│   │   └── main.jsx
├── smart-contract/      # Código Solidity do contrato inteligente
│   └── PrestacaoServicoJuridico.sol
├── README.md            # Instruções de uso
└── .env.example         # Configuração da RPC e conta
