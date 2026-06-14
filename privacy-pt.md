---
layout: default
title: Política de Privacidade
permalink: /privacy-pt/
---

# MedTime (İlaçVakti) — Política de Privacidade

**Última atualização:** 17 de maio de 2026

O MedTime (İlaçVakti) é um aplicativo móvel desenvolvido pelo Farmacêutico **Mehmet Tuğberk Özsoy**, projetado para ajudar os usuários a controlar seus medicamentos. Sua privacidade é nossa prioridade máxima; esta política explica de forma transparente quais dados são tratados e como.

Outros idiomas: [English](/ilacvakti-legal/privacy-en/) · [Türkçe](/ilacvakti-legal/privacy-tr/)

---

## 1. Dados Não Coletados

O MedTime **não** coleta identificadores pessoais (nome, e-mail, telefone, número de identidade, data de nascimento, etc.) dos usuários, não os envia aos nossos servidores e não os compartilha com terceiros. Não é necessário criar conta; o aplicativo funciona inteiramente de forma **anônima**.

Lista detalhada dos dados não coletados:
- ❌ Rastreamento para publicidade ou análise
- ❌ Serviços de análise de terceiros (Google Analytics, Facebook Pixel, etc.)
- ❌ Dados de localização
- ❌ Contatos, calendário, microfone
- ❌ Criação de conta, e-mail, telefone
- ❌ Dados do Apple Health

---

## 2. Armazenamento Local (Dados Mantidos no Seu Dispositivo)

Todas as informações que você insere são armazenadas **apenas na memória interna do seu dispositivo**:

- Nomes de medicamentos, dosagens, horários de lembrete
- Nomes de perfil (nomes que você fornece) e foto de perfil opcional
- Informações de estoque de medicamentos e fotos
- Histórico de tratamento, registros de doses tomadas/ignoradas
- Dados de sequência (streak) e conquistas (badges)
- Relatórios e anotações de saúde adicionados manualmente
- Preferências de tema, idioma, som de notificação e configurações

Quando você exclui o aplicativo, todos esses dados são excluídos junto com o seu dispositivo.

---

## 3. Permissões

### 3.1 Notificações
A permissão de notificação é solicitada para lembretes de medicamentos. As notificações são agendadas **localmente no seu dispositivo**; nenhuma conexão com servidor está envolvida.

### 3.2 Câmera
O acesso à câmera é solicitado apenas na tela *"Adicionar Medicamento"*, para escanear códigos de barras/QR nas caixas de medicamentos ou para fotografar o medicamento. As imagens da câmera não são enviadas a um servidor.

### 3.3 Fotos
O acesso à biblioteca de fotos é solicitado de forma opcional, caso você queira adicionar fotos de medicamentos ou de perfil. As fotos selecionadas são copiadas apenas para a pasta interna do aplicativo no seu dispositivo.

### 3.4 Consulta de Medicamento por Código de Barras
Ao escanear o código de barras/QR na caixa de um medicamento, apenas o **número do código de barras** é enviado a um serviço de banco de dados de medicamentos chamado NosyAPI para obter o nome e os detalhes do medicamento (bula, data de validade, etc.). Nenhuma informação pessoal (seu nome, dados de perfil, dados de saúde, fotos ou imagens da câmera) é incluída nessa consulta — apenas o número do código de barras do produto escaneado é transmitido. Este recurso é opcional; se você não escanear um código de barras, nenhum dado é enviado.

Você pode revogar as permissões a qualquer momento em iOS *Ajustes &gt; MedTime*.

---

## 4. Relatórios de Falhas (Sentry)

Para melhorar a estabilidade do aplicativo, relatórios anônimos de falhas são coletados por meio do serviço **Sentry**.

**Coletado:**
- Data e hora da falha, modelo do dispositivo, versão do iOS, versão do aplicativo
- Mensagem de erro e rastreamento técnico de pilha (stack trace)
- Contexto técnico anterior à falha (por exemplo, telas abertas)

**Não coletado:**
- Nome de usuário, e-mail, endereço IP (`sendDefaultPii` desativado)
- Capturas de tela, dados pessoais de medicamentos, dados de saúde
- Fotos ou conteúdo de relatórios

Os dados do Sentry são usados exclusivamente para a melhoria do aplicativo; **nunca** para marketing ou publicidade. Os dados do Sentry são retidos por até **90 dias**.

Política de privacidade do Sentry: <https://sentry.io/privacy/>

---

## 5. Assinatura Premium e RevenueCat

O MedTime oferece uma **assinatura Premium** opcional:

| Plano | Preço | Recursos |
|---|---|---|
| Mensal | aprox. $0,99 | Renovação automática |
| Anual | aprox. $5,99 | Inclui **teste gratuito de 7 dias**, renovação automática |

### Gerenciamento da Assinatura
- As assinaturas se renovam automaticamente; a cobrança é feita na sua conta do iTunes caso não seja cancelada com pelo menos **24 horas** de antecedência em relação ao fim do período atual.
- Cancelamento: iOS *Ajustes → Apple ID → Assinaturas*.
- O **Compartilhamento Familiar** está habilitado — uma assinatura pode ser compartilhada com até 5 membros da família.
- Os pagamentos são processados pela Apple; o MedTime não tem acesso às informações do cartão.

### Acesso Gratuito Vitalício para Usuários Anteriores
Os usuários que instalaram a versão **2.0.1 (build 5) ou anterior** recebem automaticamente acesso **Premium gratuito vitalício**. Isso é verificado de forma anônima no dispositivo usando o campo `originalApplicationVersion` do recibo da Apple.

### RevenueCat (Validação da Assinatura)
O serviço **RevenueCat** é usado para validar o estado da assinatura. Um identificador anônimo (App User ID) derivado do seu Apple ID e os dados do recibo da Apple são enviados ao RevenueCat. Seu nome, e-mail ou informações de contato **não são compartilhados**.

Política de privacidade do RevenueCat: <https://www.revenuecat.com/privacy/>

### Termos de Uso
Aplica-se o EULA Padrão da Apple: <https://www.apple.com/legal/internet-services/itunes/dev/stdeula/>

---

## 6. Compartilhamento de Dados

O MedTime **não compartilha os dados dos usuários com terceiros, não os vende e não os utiliza para fins de marketing**. As únicas exceções são:

- A consulta por código de barras descrita na Seção 3.4 (NosyAPI) — apenas o número do código de barras do produto escaneado é transmitido; não contém nenhum dado pessoal.
- Os relatórios anônimos de falhas descritos na Seção 4 (Sentry).
- Os dados anônimos de validação de assinatura descritos na Seção 5 (RevenueCat + Apple).

---

## 7. Seus Direitos sob o GDPR (Usuários da UE)

Se você reside na UE, sob o Regulamento Geral sobre a Proteção de Dados (GDPR) você tem o direito de **acessar, corrigir, excluir, opor-se ao tratamento e à portabilidade dos dados**. Nossas bases legais são: necessidade para a prestação do serviço (Artigo 6(1)(b)) e interesse legítimo para o relato de erros (Artigo 6(1)(f)).

---

## 8. Seus Direitos sob a KVKK Turca

Sob a Lei Turca de Proteção de Dados Pessoais (KVKK), Artigo 11, você tem direitos que incluem: saber se seus dados são tratados, solicitar informações, solicitar correção ou exclusão, conhecer os terceiros para os quais os dados foram transferidos, opor-se a resultados de tratamento automatizado e pleitear indenização. Para exercer esses direitos, entre em contato pelo e-mail <ilacvaktidestek@gmail.com>. As solicitações são respondidas em até **30 dias**.

---

## 9. Privacidade das Crianças

O aplicativo é classificado como **4+**. Não coletamos dados de crianças menores de 13 anos de forma consciente. Se um responsável usar o aplicativo para adicionar o perfil de uma criança (membro da família), os dados do perfil permanecem armazenados apenas localmente no dispositivo.

---

## 10. Segurança dos Dados

Como seus dados são armazenados majoritariamente no seu dispositivo, eles são protegidos pela criptografia de hardware do iOS (Secure Enclave). A comunicação com serviços de terceiros é criptografada por HTTPS.

---

## 11. Alterações nesta Política

Podemos atualizar esta política periodicamente. Alterações significativas serão anunciadas por meio de notificação no aplicativo ou das notas de versão. Por favor, consulte regularmente a data de *Última atualização*.

---

## 12. Contato

E-mail: <ilacvaktidestek@gmail.com>
