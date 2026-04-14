![AWS CCP Game](static/logo.png)

## 📖 Sobre o Projeto

**AWS CCP Game** é um jogo educacional gamificado desenvolvido para ensinar **224 serviços AWS** de forma interativa e divertida através de uma narrativa de detetive.

### 🎯 Objetivo

Você é um **Detetive** convocado para capturar o vilão **CÁLCULUS**, que hackeou os sistemas da cidade. Para capturá-lo, você precisará dominar 224 serviços AWS através de 17 fases progressivas repletas de desafios.

---

## ✨ Características

- 🎮 **17 Fases Temáticas** com narrativa progressiva
- ☁️ **224 Serviços AWS** para memorizar
- 🤖 **Sistema de Dicas com IA** - Ajuda quando necessário
- 🖥️ **Interface Terminal MS-DOS** - Visual retrô nostálgico
- 🎓 **Certificado Digital** - Emitido ao completar o jogo
- 📊 **Barra de Progresso** - Acompanhe sua evolução
- 💾 **Validação Inteligente** - Case-insensitive

---

## 🚀 Como Jogar Localmente

1. **Clone o repositório:**
```bash
git clone https://github.com/aryribeiro/aws-ccp-game.git
cd aws-ccp-game
```

2. **Crie um ambiente virtual:**
```bash
python -m venv .venv
```

3. **Ative o ambiente virtual:**

**Windows:**
```bash
.venv\Scripts\activate
```

**Linux/Mac:**
```bash
source .venv/bin/activate
```

4. **Instale as dependências:**
```bash
pip install -r requirements.txt
```

5. **Execute o jogo:**
```bash
streamlit run app.py
```

6. **Abra no navegador:**
```
http://localhost:8501
```

---

## 🎯 Fases do Jogo

| Fase | Nome | Serviços |
|------|------|----------|
| 1 | Entrando na Nuvem | 10 |
| 2 | Poder de Computação | 10 |
| 3 | Cofre de Dados | 10 |
| 4 | Bases de Conhecimento | 10 |
| 5 | Conectando o Mundo | 10 |
| 6 | Fortaleza Digital | 10 |
| 7 | Mineração de Insights | 10 |
| 8 | Inteligência Artificial | 10 |
| 9 | Automação Total | 10 |
| 10 | Containers em Ação | 10 |
| 11 | Sem Servidores | 10 |
| 12 | Jornada para a Nuvem | 10 |
| 13 | Internet das Coisas | 10 |
| 14 | Streaming de Mídia | 10 |
| 15 | Olhos na Infraestrutura | 10 |
| 16 | Serviços Avançados | 20 |
| 17 | DOMÍNIO COMPLETO DA AWS | 54 |

**Total: 224 Serviços AWS**

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.11+**
- **Streamlit** - Framework web para aplicações de dados
- **Pillow (PIL)** - Geração de certificados em imagem
- **JSON** - Armazenamento de dados dos serviços AWS

---

## 📁 Estrutura do Projeto

```
aws-ccp-game/
├── static/
│   ├── logo.png              # Logo do jogo
│   ├── assinatura.png        # Assinatura para certificado
│   └── comandos.backup       # Backup dos comandos
├── app.py                    # Aplicação principal
├── comandos.json             # 224 serviços AWS com descrições
├── requirements.txt          # Dependências Python
├── README.md                 # Documentação
└── .gitignore               # Arquivos ignorados pelo Git
```

## 🎓 Certificado

Ao completar todas as 17 fases e dominar os 224 serviços AWS, você receberá um **Certificado Digital** personalizado com:

- ✅ Seu nome
- ✅ Data de conclusão
- ✅ Carga horária estimada: 4 horas
- ✅ Logo oficial do jogo
- ✅ Assinatura digital
- ✅ Download em PNG de alta qualidade

---

## 🎮 Como Funciona

1. **Digite seu nome** de detetive na tela inicial (será usado no certificado)
2. **Leia a dica** fornecida pela IA sobre o serviço AWS
3. **Digite o nome do serviço** (ex: EC2, S3, Lambda)
4. **Pressione ENTER** para validar
5. **Pedir ajuda** se necessário (mostra a resposta)
6. **Avance pelas fases** até capturar o CÁLCULUS!

---

## 📊 Categorias de Serviços AWS

O jogo abrange todas as principais categorias de serviços AWS:

- ☁️ **Computação** - EC2, Lambda, Lightsail, Batch, ECS, EKS
- 💾 **Armazenamento** - S3, EFS, FSx, Glacier, Storage Gateway
- 🗄️ **Banco de Dados** - RDS, DynamoDB, Aurora, Neptune, DocumentDB
- 🌐 **Rede** - VPC, CloudFront, Route 53, Direct Connect, API Gateway
- 🔒 **Segurança** - IAM, GuardDuty, Inspector, Macie, WAF, Shield
- 📊 **Analytics** - Athena, Redshift, Kinesis, QuickSight, EMR
- 🤖 **Machine Learning** - SageMaker, Bedrock, Rekognition, Comprehend
- 🔧 **Gerenciamento** - CloudWatch, CloudFormation, Systems Manager
- 📱 **Mobile & IoT** - IoT Core, Amplify, AppSync, Device Farm
- 🎬 **Mídia** - MediaConvert, MediaLive, IVS, Kinesis Video Streams
- 🎮 **Gaming** - GameLift
- 🔬 **Outros** - Quantum (Braket), Blockchain, Satellite (Ground Station)

---

## 🚀 Deploy

### Streamlit Cloud (Recomendado)

1. Faça fork ou clone este repositório
2. Acesse [share.streamlit.io](https://share.streamlit.io/)
3. Conecte sua conta GitHub
4. Selecione o repositório `aws-ccp-game`
5. Deploy automático!

### Outras Plataformas

- **Render** - Suporta Streamlit nativamente
- **Railway** - Deploy fácil com créditos gratuitos
- **Heroku** - Requer configuração adicional (Procfile)

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/NovaFuncionalidade`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`)
4. Push para a branch (`git push origin feature/NovaFuncionalidade`)
5. Abrir um Pull Request

---

## 📝 Melhorias Futuras

- [ ] Sistema de save/load de progresso
- [ ] Ranking/leaderboard online
- [ ] Sons de feedback
- [ ] Modo de dificuldade (fácil/médio/difícil)
- [ ] Conquistas/badges
- [ ] Modo multiplayer
- [ ] Analytics de progresso
- [ ] Versão mobile otimizada
- [ ] Suporte a múltiplos idiomas

---

## 📄 Licença

Este projeto é de código aberto e está disponível para uso educacional.

---

### Terminal de Jogo
Interface estilo MS-DOS com feedback em tempo real

### Certificado
Certificado digital personalizado ao completar o jogo

---

## ⚠️ Observações

- **Testado apenas em desktop** - Melhor experiência em computador
- **Requer conexão com internet** - Para carregar fontes e recursos
- **Navegadores recomendados** - Chrome, Firefox, Edge (atualizados)
- **Tempo estimado** - 4 horas para completar todas as fases

---

## 🎯 Objetivo Educacional

Este jogo foi desenvolvido para ajudar estudantes e iniciantes AWS a:

- ✅ Memorizar os principais serviços AWS
- ✅ Entender as categorias de serviços
- ✅ Preparar-se para certificação AWS CCP
- ✅ Aprender de forma gamificada e divertida
- ✅ Ter uma visão geral do ecossistema AWS

---

**⭐ Se este projeto te ajudou, deixe uma estrela no GitHub! ⭐**


**Ary Ribeiro**

- 📧 Email: [aryribeiro@gmail.com](mailto:aryribeiro@gmail.com)
- 🌐 LinkedIn: [@aryribeiro](https://linkedin.com/in/aryribeiro)
- 🐙 GitHub: [@aryribeiro](https://github.com/aryribeiro)
