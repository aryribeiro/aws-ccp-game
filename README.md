Obs.: caso o app esteja no modo "sleeping" (dormindo) ao entrar, basta clicar no botão que estará disponível e aguardar, para ativar o mesmo. É um comportamento normal, do Streamlit Cloud.
![AWS CCP Game](static/logo.png)

## 📖 Sobre o Projeto

**AWS CCP Game** é um jogo educacional gamificado desenvolvido para ensinar **235 serviços AWS** de forma interativa e divertida através de uma narrativa de detetive.

### 🎯 Objetivo

Você é um **Detetive** convocado para capturar o vilão **CÁLCULUS**, que hackeou os sistemas da cidade. Para capturá-lo, você precisará dominar 235 serviços AWS através de 23 fases progressivas organizadas pelas categorias oficiais da AWS 2026.

---

## ✨ Características

- 🎮 **23 Fases Oficiais** organizadas pelas categorias AWS 2026
- ☁️ **235 Serviços AWS** para memorizar
- 🤖 **Sistema de Dicas com IA** - Ajuda quando necessário
- 🖥️ **Interface Terminal MS-DOS** - Visual retrô nostálgico
- 🎓 **Certificado Digital** - Emitido ao completar o jogo
- 📊 **Barra de Progresso** - Acompanhe sua evolução
- 💾 **Validação Inteligente** - Case-insensitive
- 🎯 **Sem Spoilers** - Siglas não reveladas nas descrições

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

## 🎯 Fases do Jogo (Categorias Oficiais AWS 2026)

| Fase | Categoria Oficial | Serviços |
|------|-------------------|----------|
| 1 | Computação | 11 |
| 2 | Contêineres | 4 |
| 3 | Armazenamento | 8 |
| 4 | Banco de Dados | 10 |
| 5 | Migração e Transferência | 10 |
| 6 | Redes e Entrega de Conteúdo | 12 |
| 7 | Ferramentas do Desenvolvedor | 16 |
| 8 | Capacitação do Cliente | 5 |
| 9 | Blockchain | 1 |
| 10 | Satélite | 1 |
| 11 | Quantum Technologies | 1 |
| 12 | Gerenciamento e Governança | 29 |
| 13 | Serviços de Mídia | 11 |
| 14 | Machine Learning | 28 |
| 15 | Análise de Dados | 20 |
| 16 | Segurança, Identidade e Conformidade | 26 |
| 17 | Cloud Financial Management | 3 |
| 18 | Dispositivos Móveis | 4 |
| 19 | Integração de Aplicativos | 9 |
| 20 | Aplicativos Empresariais | 12 |
| 21 | Computação de Usuário Final | 4 |
| 22 | Internet das Coisas | 8 |
| 23 | Desenvolvimento de Jogos | 2 |

**Total: 235 Serviços AWS**

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
│   └── som.mp3               # Música de fundo
├── app.py                    # Aplicação principal
├── comandos.json             # 235 serviços AWS com descrições
├── requirements.txt          # Dependências Python
├── packages.txt              # Pacotes do sistema (fontes)
├── README.md                 # Documentação
└── .gitignore               # Arquivos ignorados pelo Git
```

## 🎓 Certificado

Ao completar todas as 23 fases e dominar os 235 serviços AWS, você receberá um **Certificado Digital** personalizado com:

- ✅ Seu nome
- ✅ Data de conclusão
- ✅ Carga horária estimada: 4 horas
- ✅ Logo oficial do jogo
- ✅ Assinatura digital
- ✅ Download em PNG de alta qualidade
- ✅ Menção aos 235 serviços dominados

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

O jogo abrange todas as 23 categorias oficiais de serviços AWS 2026:

- ☁️ **Computação** - EC2, Lambda, Lightsail, Batch, Elastic Beanstalk, App Runner
- 📦 **Contêineres** - ECS, EKS, ECR, Red Hat OpenShift Service on AWS
- 💾 **Armazenamento** - S3, EFS, FSx, Glacier, Storage Gateway, AWS Backup
- 🗄️ **Banco de Dados** - RDS, Aurora, DynamoDB, Neptune, DocumentDB, Keyspaces, Timestream
- 🚚 **Migração e Transferência** - Migration Hub, DMS, DataSync, Snow Family, Transfer Family
- 🌐 **Redes e Entrega de Conteúdo** - VPC, CloudFront, Route 53, Direct Connect, API Gateway
- 🔧 **Ferramentas do Desenvolvedor** - CodeCommit, CodeBuild, CodeDeploy, CodePipeline, Cloud9, X-Ray
- 🎓 **Capacitação do Cliente** - AWS Skill Builder, Training and Certification, re:Post
- ⛓️ **Blockchain** - Managed Blockchain
- 🛰️ **Satélite** - Ground Station
- ⚛️ **Quantum Technologies** - Amazon Braket
- 🎛️ **Gerenciamento e Governança** - CloudWatch, CloudFormation, Systems Manager, Control Tower, Organizations
- 🎬 **Serviços de Mídia** - MediaConvert, MediaLive, IVS, Kinesis Video Streams, Elemental
- 🤖 **Machine Learning** - SageMaker, Bedrock, Rekognition, Comprehend, Lex, Polly, Transcribe
- 📊 **Análise de Dados** - Athena, Redshift, Kinesis, QuickSight, EMR, Glue, OpenSearch
- 🔒 **Segurança, Identidade e Conformidade** - IAM, GuardDuty, Inspector, Macie, WAF, Shield, Cognito, KMS
- 💰 **Cloud Financial Management** - Cost Explorer, Budgets, Billing Conductor
- 📱 **Dispositivos Móveis** - Amplify, AppSync, Device Farm, Location Service
- 🔗 **Integração de Aplicativos** - EventBridge, SNS, SQS, Step Functions, AppFlow, MQ
- 🏢 **Aplicativos Empresariais** - WorkSpaces, WorkMail, Connect, Chime, Supply Chain
- 🖥️ **Computação de Usuário Final** - WorkSpaces, WorkSpaces Applications, Thin Client, Secure Browser
- 🌐 **Internet das Coisas** - IoT Core, IoT Greengrass, IoT SiteWise, IoT Events, IoT Device Management
- 🎮 **Desenvolvimento de Jogos** - GameLift Servers, GameLift Streams

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

Este jogo foi desenvolvido para ajudar estudantes e profissionais AWS a:

- ✅ Memorizar os 235 principais serviços AWS
- ✅ Entender as 23 categorias oficiais da AWS 2026
- ✅ Preparar-se para certificação AWS Cloud Practitioner
- ✅ Aprender de forma gamificada e divertida
- ✅ Ter uma visão completa do ecossistema AWS
- ✅ Treinar memória sem spoilers de siglas

---

**⭐ Se este projeto te ajudou, deixe uma estrela no GitHub! ⭐**


**Ary Ribeiro**

- 📧 Email: [aryribeiro@gmail.com](mailto:aryribeiro@gmail.com)
- 🌐 LinkedIn: [@aryribeiro](https://linkedin.com/in/aryribeiro)
- 🐙 GitHub: [@aryribeiro](https://github.com/aryribeiro)
