# Carlo Bolt Test App

Este é um aplicativo Flask simples para testar o sistema Carlo Bolt.

## 🚀 Funcionalidades

- ✅ Página inicial com interface moderna
- ✅ API de status em tempo real
- ✅ Health check endpoint
- ✅ Testes de API via interface web
- ✅ Deploy automático via Carlo Bolt

## 📁 Estrutura

```
flask-test/
├── app.py              # Aplicação Flask principal
├── requirements.txt    # Dependências Python
├── templates/
│   └── index.html     # Template da página inicial
└── README.md          # Este arquivo
```

## 🔧 Como Usar

1. **Localmente:**
   ```bash
   pip install -r requirements.txt
   python app.py
   ```

2. **Via Carlo Bolt:**
   - Criar site no Carlo Bolt
   - Configurar repositório GitHub
   - Habilitar auto-deploy

## 📊 Endpoints

- `GET /` - Página inicial
- `GET /api/status` - Status do sistema
- `GET /api/test` - Teste da API
- `GET /health` - Health check

## 🎯 Objetivo

Testar o fluxo completo do Carlo Bolt:
1. ✅ Criação de site
2. ✅ Download do GitHub
3. ✅ Instalação de dependências
4. ✅ Configuração de ambiente
5. ✅ Deploy automático
6. ✅ SSL setup
7. ✅ Logs e monitoramento

---

**Criado para testar o sistema Carlo Bolt** 🚀 